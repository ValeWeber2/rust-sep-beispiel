FROM rust:1.99

RUN apt-get update && apt-get install -y \
    && rm -rf /var/lib/apt/lists/*

RUN rustup component add clippy rustfmt

ENV CARGO_HOME=/usr/local/cargo
ENV PATH="$CARGO_HOME/bin:${PATH}"

WORKDIR /workspaces/Beispiel
