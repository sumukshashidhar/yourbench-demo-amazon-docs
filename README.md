# yourbench-demo-amazon-docs

This is a minimal example of using [yourbench](https://github.com/huggingface/yourbench) to generate a dataset of questions from a piece of documentation.

## Usage

```bash
# Install yourbench
pip install yourbench

# set an anthropic api key, or use any other model
export ANTHROPIC_API_KEY=<your-anthropic-api-key>

# Run the example
yourbench run --config config.yaml
```

And that's it! Modify the config.yaml to your liking!
