# Build Stage
FROM fuzzers/atheris:2.0.7-python3.9

# Install dependencies
RUN pip install dictdiffer

CMD ["/src/mayhem/fuzz_differ.py"]