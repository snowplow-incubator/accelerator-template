[![Discourse posts][discourse-image]][discourse] 
[![License][license-image]][license] 

![snowplow-logo](https://raw.githubusercontent.com/snowplow/dbt-snowplow-utils/main/assets/snowplow_logo.png)


# Snowplow Accelerator Template

This is a template for a Snowplow accelerator. Instructions on set up can be viewed [here](https://docs.snowplow.io/accelerators/template/)

## Installation

Recursively update the git submodules:

```sh
git submodule update --init --recursive
```

To build the Hugo app:

```sh
./scripts/build.sh build
```

## Usage

To start an HTTP server serving the app, use:

```sh
./scripts/build.sh serve
```

This will run `hugo server` on the background.

### Other Accelerators

You can find a list of all our live accelerators on the [Snowplow Website](https://snowplow.io/data-product-accelerators/).

### Join the Snowplow community

We welcome all ideas, questions and contributions!

For support requests, please use our community support [Discourse][discourse] forum.

If you find a bug, please report an issue on GitHub.

### Copyright and license

The <YOUR ACCELERATOR HERE> accelerator is Copyright 2022 Snowplow Analytics Ltd.

Licensed under the [Apache License, Version 2.0][license] (the "License");
you may not use this software except in compliance with the License.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

[license]: http://www.apache.org/licenses/LICENSE-2.0
[license-image]: http://img.shields.io/badge/license-Apache--2-blue.svg?style=flat

[discourse-image]: https://img.shields.io/discourse/posts?server=https%3A%2F%2Fdiscourse.snowplow.io%2F
[discourse]: http://discourse.snowplow.io/
