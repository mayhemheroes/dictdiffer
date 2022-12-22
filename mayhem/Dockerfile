# Build Stage
FROM fuzzers/atheris:2.0.7-python3.9

# Install dependencies
RUN pip install dictdiffer
ADD ./mayhem/fuzz_differ.py /fuzz_differ.py
CMD ["/fuzz_differ.py"]