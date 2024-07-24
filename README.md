# Haystack 2.x Core Integrations

This repository contains integrations to extend the capabilities of [Haystack](https://github.com/deepset-ai/haystack) version 2.0 and
onwards. The code in this repo is maintained by [deepset](https://www.deepset.ai), see each integration's `README` file for details around installation, usage and support.

## Quick start

You will need `hatch` to work on or create new integrations, open [this link](https://hatch.pypa.io/latest/install/#installation)
and follow the install instructions for your operating system and platform.

All the integrations are self contained, so the first step before working on one is to `cd` into the proper folder.
For example, to run the tests suite for the Chroma document store, from the root of the repo:

```sh
$ cd integrations/chroma
$ hatch run test
```

Hatch will take care of setting up an isolated Python environment and run the tests.

Please check out our [Contribution Guidelines](CONTRIBUTING.md) for all the details.

## Inventory

| Package                                                                                                        | Type                | PyPi Package                                                                                                                                             | Status                                                                                                                                                                                                                                               |
|----------------------------------------------------------------------------------------------------------------|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [amazon-bedrock-haystack](integrations/amazon_bedrock/)                                                        | Generator           | [![PyPI - Version](https://img.shields.io/pypi/v/amazon-bedrock-haystack.svg)](https://pypi.org/project/amazon-bedrock-haystack)                         | [![Test / amazon_bedrock](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/amazon_bedrock.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/amazon_bedrock.yml)                   |
| [amazon-sagemaker-haystack](integrations/amazon_sagemaker/)                                                    | Generator           | [![PyPI - Version](https://img.shields.io/pypi/v/amazon-sagemaker-haystack.svg)](https://pypi.org/project/amazon-sagemaker-haystack)                     | [![Test / amazon_sagemaker](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/amazon_sagemaker.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/amazon_sagemaker.yml)             |
| [anthropic-haystack](integrations/anthropic/)                                                                  | Generator           | [![PyPI - Version](https://img.shields.io/pypi/v/anthropic-haystack.svg)](https://pypi.org/project/anthropic-haystack)                                   | [![Test / anthropic](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/anthropic.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/anthropic.yml)                                  |
| [astra-haystack](integrations/astra/)                                                                          | Document Store      | [![PyPI - Version](https://img.shields.io/pypi/v/astra-haystack.svg)](https://pypi.org/project/astra-haystack)                                           | [![Test / astra](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/astra.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/astra.yml)                                              |
| [chroma-haystack](integrations/chroma/)                                                                        | Document Store      | [![PyPI - Version](https://img.shields.io/pypi/v/chroma-haystack.svg)](https://pypi.org/project/chroma-haystack)                                         | [![Test / chroma](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/chroma.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/chroma.yml)                                           |
| [cohere-haystack](integrations/cohere/)                                                                        | Embedder, Generator, Ranker | [![PyPI - Version](https://img.shields.io/pypi/v/cohere-haystack.svg)](https://pypi.org/project/cohere-haystack)                                         | [![Test / cohere](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/cohere.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/cohere.yml)                                           |
| [deepeval-haystack](integrations/deepeval/)                                                                    | Evaluator           | [![PyPI - Version](https://img.shields.io/pypi/v/deepeval-haystack.svg)](https://pypi.org/project/deepeval-haystack)                                     | [![Test / deepeval](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/deepeval.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/deepeval.yml)                                     |
| [elasticsearch-haystack](integrations/elasticsearch/)                                                          | Document Store      | [![PyPI - Version](https://img.shields.io/pypi/v/elasticsearch-haystack.svg)](https://pypi.org/project/elasticsearch-haystack)                           | [![Test / elasticsearch](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/elasticsearch.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/elasticsearch.yml)                      |
| [fastembed-haystack](integrations/fastembed/)                                                                  | Embedder            | [![PyPI - Version](https://img.shields.io/pypi/v/fastembed-haystack.svg)](https://pypi.org/project/fastembed-haystack/)                                  | [![Test / fastembed](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/fastembed.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/fastembed.yml)                                  |
| [google-ai-haystack](integrations/google_ai/)                                                                  | Generator           | [![PyPI - Version](https://img.shields.io/pypi/v/google-ai-haystack.svg)](https://pypi.org/project/google-ai-haystack)                                   | [![Test / google-ai](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/google_ai.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/google_ai.yml)                                  |
| [google-vertex-haystack](integrations/google_vertex/)                                                          | Generator           | [![PyPI - Version](https://img.shields.io/pypi/v/google-vertex-haystack.svg)](https://pypi.org/project/google-vertex-haystack)                           | [![Test / google-vertex](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/google_vertex.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/google_vertex.yml)                      |
| [gradient-haystack](integrations/gradient/)                                                                    | Embedder, Generator | [![PyPI - Version](https://img.shields.io/pypi/v/gradient-haystack.svg)](https://pypi.org/project/gradient-haystack)                                     | [![Test / gradient](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/gradient.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/gradient.yml)                                     |
| [instructor-embedders-haystack](integrations/instructor_embedders/)                                            | Embedder            | [![PyPI - Version](https://img.shields.io/pypi/v/instructor-embedders-haystack.svg)](https://pypi.org/project/instructor-embedders-haystack)             | [![Test / instructor-embedders](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/instructor_embedders.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/instructor_embedders.yml) |
| [jina-haystack](integrations/jina/)                                                                            | Embedder, Ranker    | [![PyPI - Version](https://img.shields.io/pypi/v/jina-haystack.svg)](https://pypi.org/project/jina-haystack)                                             | [![Test / jina](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/jina.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/jina.yml)                                                 |
| [langfuse-haystack](integrations/langfuse/)                                                                    | Tracer              | [![PyPI - Version](https://img.shields.io/pypi/v/langfuse-haystack.svg?color=orange)](https://pypi.org/project/langfuse-haystack)                        | [![Test / langfuse](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/langfuse.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/langfuse.yml)                                     |
| [llama-cpp-haystack](integrations/llama_cpp/)                                                                  | Generator           | [![PyPI - Version](https://img.shields.io/pypi/v/llama-cpp-haystack.svg?color=orange)](https://pypi.org/project/llama-cpp-haystack)                      | [![Test / llama-cpp](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/llama_cpp.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/llama_cpp.yml)                                  |
| [mistral-haystack](integrations/mistral/)                                                                      | Embedder, Generator | [![PyPI - Version](https://img.shields.io/pypi/v/mistral-haystack.svg)](https://pypi.org/project/mistral-haystack)                                       | [![Test / mistral](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/mistral.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/mistral.yml)                                        |
| [mongodb-atlas-haystack](integrations/mongodb_atlas/)                                                          | Document Store      | [![PyPI - Version](https://img.shields.io/pypi/v/mongodb-atlas-haystack.svg?color=orange)](https://pypi.org/project/mongodb-atlas-haystack)              | [![Test / mongodb-atlas](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/mongodb_atlas.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/mongodb_atlas.yml)                      |
| [nvidia-haystack](integrations/nvidia/)                                                                        | Generator           | [![PyPI - Version](https://img.shields.io/pypi/v/nvidia-haystack.svg?color=orange)](https://pypi.org/project/nvidia-haystack)                            | [![Test / nvidia](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/nvidia.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/nvidia.yml)                                           |
| [ollama-haystack](integrations/ollama/)                                                                        | Generator           | [![PyPI - Version](https://img.shields.io/pypi/v/ollama-haystack.svg?color=orange)](https://pypi.org/project/ollama-haystack)                            | [![Test / ollama](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/ollama.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/ollama.yml)                                           |
| [opensearch-haystack](integrations/opensearch/)                                                                | Document Store      | [![PyPI - Version](https://img.shields.io/pypi/v/opensearch-haystack.svg)](https://pypi.org/project/opensearch-haystack)                                 | [![Test / opensearch](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/opensearch.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/opensearch.yml)                               |
| [optimum-haystack](integrations/optimum/)                                                                      | Embedder            | [![PyPI - Version](https://img.shields.io/pypi/v/optimum-haystack.svg)](https://pypi.org/project/optimum-haystack)                                       | [![Test / optimum](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/optimum.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/optimum.yml)                                        |
| [pinecone-haystack](integrations/pinecone/)                                                                    | Document Store      | [![PyPI - Version](https://img.shields.io/pypi/v/pinecone-haystack.svg?color=orange)](https://pypi.org/project/pinecone-haystack)                        | [![Test / pinecone](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/pinecone.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/pinecone.yml)                                     |
| [pgvector-haystack](integrations/pgvector/)                                                                    | Document Store      | [![PyPI - Version](https://img.shields.io/pypi/v/pgvector-haystack.svg?color=orange)](https://pypi.org/project/pgvector-haystack)                        | [![Test / pgvector](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/pgvector.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/pgvector.yml)                                     |
| [qdrant-haystack](integrations/qdrant/)                                                                        | Document Store      | [![PyPI - Version](https://img.shields.io/pypi/v/qdrant-haystack.svg?color=orange)](https://pypi.org/project/qdrant-haystack)                            | [![Test / qdrant](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/qdrant.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/qdrant.yml)                                           |
| [ragas-haystack](integrations/ragas/)                                                                          | Evaluator           | [![PyPI - Version](https://img.shields.io/pypi/v/ragas-haystack.svg)](https://pypi.org/project/ragas-haystack)                                           | [![Test / ragas](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/ragas.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/ragas.yml)                                              |
| [unstructured-fileconverter-haystack](integrations/unstructured/)                                              | File converter      | [![PyPI - Version](https://img.shields.io/pypi/v/unstructured-fileconverter-haystack.svg)](https://pypi.org/project/unstructured-fileconverter-haystack) | [![Test / unstructured](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/unstructured.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/unstructured.yml)                         |
| [uptrain-haystack](https://github.com/deepset-ai/haystack-core-integrations/tree/staging/integrations/uptrain) | Evaluator           | [![PyPI - Version](https://img.shields.io/pypi/v/uptrain-haystack.svg)](https://pypi.org/project/uptrain-haystack)                                       | [Staged](https://docs.haystack.deepset.ai/docs/breaking-change-policy#discontinuing-an-integration)                                                                                                                                                                                                                                               |
| [weaviate-haystack](integrations/weaviate/)                                                                    | Document Store      | [![PyPI - Version](https://img.shields.io/pypi/v/weaviate-haystack.svg)](https://pypi.org/project/weaviate-haystack)                                     | [![Test / weaviate](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/weaviate.yml/badge.svg)](https://github.com/deepset-ai/haystack-core-integrations/actions/workflows/weaviate.yml)                                     |

## Releasing

> [!NOTE]
> Only maintainers can release new versions of integrations.
> If you're a community contributor and want to release a new version of an integration,
> reach out to a maintainer.

To release a new version of an integration to PyPI tag the commit with the right version number and push the tag to 
GitHub. The GitHub Actions workflow will take care of the rest.

1. Tag the commit with the right version number

    The tag needs to have the following format:

    ```
    git tag integrations/<INTEGRATION_FOLDER_NAME>-<version>
    ```

    For example, if we want to release version 1.0.99 of the google-vertex-haystack integration we'd have to push the tag:

    ```
    git tag integrations/google_vertex-v1.0.99
    ```
2. Push the tag to GitHub

    ```
    git push --tags origin
    ```
3. Wait for the CI to do its magic
