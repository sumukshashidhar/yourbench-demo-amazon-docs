# yourbench-demo-amazon-docs

This is a minimal example of using [YourBench](https://github.com/huggingface/yourbench) to generate a dataset of questions from a piece of documentation. Here's a link to a dataset that was generated using this example: [Huggingface Dataset](https://huggingface.co/datasets/sumuks/yourbench-aws-bedrock-documentation-example).

## Usage

```bash
# Install yourbench
pip install yourbench

# set an anthropic api key, or use any other model
export ANTHROPIC_API_KEY=<your-anthropic-api-key>

# Run the example
yourbench run --config config.yaml
```

And that's it! Modify the config.yaml to your liking! You may want to refer to [docs](https://github.com/huggingface/yourbench/blob/main/example/configs/advanced_example.yaml) for more knobs to turn :D

Happy evals!