<!-- markdownlint-disable -->

# Changelog

## [0.95.0](https://github.com/tiborsimko/reana-workflow-engine-serial/compare/v0.9.4...0.95.0) (2026-02-10)


### ⚠ BREAKING CHANGES

* **python:** drop support for Python 3.6 and 3.7

### Build

* **docker:** install correct extras of reana-commons submodule ([#196](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/196)) ([b23f4df](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/b23f4df602d80d62626e8e907181a8c710eb662f))
* **docker:** non-editable submodules in "latest" mode ([#190](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/190)) ([03a15cf](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/03a15cfa7973152f9923ecade412d8eab3ea80e3))
* **docker:** pin setuptools 70 ([#216](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/216)) ([f94d003](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/f94d0036ded9562155528d52f33110e43c954384))
* **docker:** pin setuptools to v70 ([#214](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/214)) ([c6ae076](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/c6ae076bf4c8be9b5018e6acb7b0f94cce134184))
* **docker:** upgrade to Ubuntu 24.04 and Python 3.12 ([#213](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/213)) ([5ded981](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/5ded981a6c4b22dc49ee4306aed860a4881c9dd3))
* **python:** add minimal `pyproject.toml` ([#214](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/214)) ([c3cd6f6](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/c3cd6f65d9450dd40a3f9c49461db27283798925))
* **python:** bump all required packages as of 2024-03-04 ([#200](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/200)) ([ffc8aec](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/ffc8aec739e2284f301586d47618ff6c4142643a))
* **python:** bump shared REANA packages as of 2024-03-04 ([#200](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/200)) ([47c26cc](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/47c26ccfbfdfc7419c4a6fab1d7abf95a667e4e2))
* **python:** bump shared REANA packages as of 2024-11-28 ([#218](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/218)) ([430fd04](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/430fd04acb6485754a0cc5fa4dbeefd3aaa022e4))
* **python:** drop support for Python 3.6 and 3.7 ([#208](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/208)) ([c5f68ab](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/c5f68aba7305f37755722a88b7a79f49a61b1ebf))
* **python:** pin setuptools below 81 ([#240](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/240)) ([ef9134c](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/ef9134ceca0e01039b150975f33eb6b5bbb81621))
* **python:** remove deprecated `pytest-runner` ([#214](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/214)) ([5beb31e](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/5beb31efbc5dd7ce688fa559621aaf63ee1ed388))
* **python:** use optional deps instead of `tests_require` ([#214](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/214)) ([906d439](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/906d4397e9670fac20c515a73eeed78567635fc3))


### Features

* **tasks:** allow Compute4PUNCH backend options ([#210](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/210)) ([a6313f2](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/a6313f22dcdcab08a84b3dd6c8ce7386122d7400))
* **tasks:** pass K8S requests/limits to job controller ([#221](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/221)) ([31bc971](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/31bc9714c578e820f7631e095af436ed22e07c37))
* **tasks:** pass K8S requests/limits to job controller ([#221](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/221)) ([9c02478](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/9c02478c32a2d340b9ef9f3ee65c1781856a3155))


### Bug fixes

* **progress:** handle stopped jobs ([#195](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/195)) ([a232a76](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/a232a76627e09bfb401de4f547540c6012357986))


### Code refactoring

* **docs:** move from reST to Markdown ([#198](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/198)) ([7507d12](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/7507d1243af43f4621e117f4f92569f4dd7271f6))


### Continuous integration

* **actions:** update GitHub actions due to Node 16 deprecation ([#204](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/204)) ([8ca85c0](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/8ca85c0b85a93b60d6202ebdd8ac955bb635a1a9))
* add hadolint and flake8 linters ([1145d9d](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/1145d9d58959261a631b738fae1732aefa8d0b79))
* added github actions workflow ([08a62e5](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/08a62e5f383132a911d6912b50442c18e395ee3d))
* **commitlint:** addition of commit message linter ([#191](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/191)) ([b7a6ef1](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/b7a6ef18dae95efae7af791094b5ff79369705b0))
* **commitlint:** allow release commit style ([#201](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/201)) ([b50b6d0](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/b50b6d0398fc6d6e4c4704d3698d811b7088921d))
* **commitlint:** check for the presence of concrete PR number ([#197](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/197)) ([1813ac3](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/1813ac3a88cd8e33a59040c6bd72ed048a151654))
* **commitlint:** fix local running of commit linter on macOS ([#229](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/229)) ([f32aafd](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/f32aafd9b482aa996f97f3bfc2131c872611016c))
* **commitlint:** improve checking of merge commits ([#215](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/215)) ([00514b3](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/00514b3639e7b2ded09953628f3ac8346ef57db2))
* **jsonlint:** add JSON linting ([#231](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/231)) ([fe84cbc](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/fe84cbc4da343e72de1f504a919981dd34677f82))
* **markdownlint:** add Markdown linting ([#231](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/231)) ([ddebde0](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/ddebde02dffc23f240847f51e065b4d07ceb7767))
* pin hadolint version ([a77f798](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/a77f7982d06be52656d7ee12f65f14264c21dd81))
* **prettier:** add Prettier code formatting checks ([#231](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/231)) ([acb707f](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/acb707fb27c8ea4884d39af4f8d2500986213ab8))
* publish docker image after new release ([d595d57](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/d595d57956811960df366ea28be30cc96742383e))
* **pytest:** invoke `pytest` directly instead of `setup.py test` ([#214](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/214)) ([3e58d5a](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/3e58d5a0dbe61c5c97c628d243cb639a0b3dfd99))
* **release-please:** initial configuration ([#191](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/191)) ([d40a675](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/d40a675cab6b6e8c7631d503358016d427bdac3c))
* **release-please:** update version in Dockerfile ([#194](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/194)) ([52c34ec](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/52c34ec2003fd09b8a65ef3cff61b7f9a105041e))
* remove older versions from python tests ([f1f583d](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/f1f583de22c2f4205110f6131a13fe986d5a6911))
* **runners:** upgrade CI runners to Ubuntu 22.04 ([#224](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/224)) ([31bc971](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/31bc9714c578e820f7631e095af436ed22e07c37))
* **runners:** upgrade CI runners to Ubuntu 22.04 ([#224](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/224)) ([1ff9187](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/1ff9187016a404aa37d06b32ea61ef17f3767b01))
* **shellcheck:** fix exit code propagation ([#197](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/197)) ([5565b29](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/5565b29ac7b431561af2cd43e6ed882bbdf57126))
* **shfmt:** add shell script formatting checks ([#231](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/231)) ([5cf4b26](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/5cf4b269f54dd9c89a7cd653f896255b3c19dc10))
* update all actions ([b12f92f](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/b12f92fdb338434eb92f56e548b973de912696a4))
* **yamllint:** add YAML linting ([#231](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/231)) ([11fa9b8](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/11fa9b8dde3ab0ab88ab632da8b7a803ec408f97))


### Documentation

* add .readthedocs.yaml to migrate to RTD v2 ([ad92e7c](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/ad92e7ccbd038f3bf3fd19f0e8e94ad68291c92d))
* add Sinclert Perez to authors ([b33fbce](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/b33fbcea987347408f684423ed018db11e5c5d9b))
* addition of overview.rst ([a6cd116](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/a6cd11659e4b8a0aa6e085926d75a6eb701c2df2))
* **authors:** complete list of contributors ([#199](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/199)) ([e9b25b6](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/e9b25b6ab37421971d02c52422ed19fce249b4ea))
* **authors:** complete list of contributors ([#232](https://github.com/tiborsimko/reana-workflow-engine-serial/issues/232)) ([edd0a08](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/edd0a085645642e6fb9b77bf86439788d56cffa6))
* new logo, panel verbiage and links ([4b3ea33](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/4b3ea33ea97faccf782ef29401b5beb7981f1a3a))
* pydocstyle fixes ([0310544](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/0310544b4fba4bc930a611d7f32cc6c766705104))
* set default language to English ([eb2ecc1](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/eb2ecc1fa6d900e7896667542292a8bf63af5003))
* single-page RTFD outline ([5bcc992](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/5bcc992ab513f96677542eeb6de7c2117442cedf))
* update changelog ([c0d90b7](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/c0d90b75a1c36df851c49732cd11cc144ec1191a))


### Chores

* **master:** release 0.95.0-alpha.1 ([5d34691](https://github.com/tiborsimko/reana-workflow-engine-serial/commit/5d34691ed5fde8d38720b742bd9921cd52b7fa0e))

## [0.9.4](https://github.com/reanahub/reana-workflow-engine-serial/compare/0.9.3...0.9.4) (2024-11-29)


### Build

* **docker:** pin setuptools 70 ([#216](https://github.com/reanahub/reana-workflow-engine-serial/issues/216)) ([f94d003](https://github.com/reanahub/reana-workflow-engine-serial/commit/f94d0036ded9562155528d52f33110e43c954384))
* **python:** bump shared REANA packages as of 2024-11-28 ([#218](https://github.com/reanahub/reana-workflow-engine-serial/issues/218)) ([430fd04](https://github.com/reanahub/reana-workflow-engine-serial/commit/430fd04acb6485754a0cc5fa4dbeefd3aaa022e4))


### Features

* **tasks:** allow Compute4PUNCH backend options ([#210](https://github.com/reanahub/reana-workflow-engine-serial/issues/210)) ([a6313f2](https://github.com/reanahub/reana-workflow-engine-serial/commit/a6313f22dcdcab08a84b3dd6c8ce7386122d7400))

## [0.9.3](https://github.com/reanahub/reana-workflow-engine-serial/compare/0.9.2...0.9.3) (2024-03-04)


### Build

* **docker:** install correct extras of reana-commons submodule ([#196](https://github.com/reanahub/reana-workflow-engine-serial/issues/196)) ([b23f4df](https://github.com/reanahub/reana-workflow-engine-serial/commit/b23f4df602d80d62626e8e907181a8c710eb662f))
* **docker:** non-editable submodules in "latest" mode ([#190](https://github.com/reanahub/reana-workflow-engine-serial/issues/190)) ([03a15cf](https://github.com/reanahub/reana-workflow-engine-serial/commit/03a15cfa7973152f9923ecade412d8eab3ea80e3))
* **python:** bump all required packages as of 2024-03-04 ([#200](https://github.com/reanahub/reana-workflow-engine-serial/issues/200)) ([ffc8aec](https://github.com/reanahub/reana-workflow-engine-serial/commit/ffc8aec739e2284f301586d47618ff6c4142643a))
* **python:** bump shared REANA packages as of 2024-03-04 ([#200](https://github.com/reanahub/reana-workflow-engine-serial/issues/200)) ([47c26cc](https://github.com/reanahub/reana-workflow-engine-serial/commit/47c26ccfbfdfc7419c4a6fab1d7abf95a667e4e2))


### Bug fixes

* **progress:** handle stopped jobs ([#195](https://github.com/reanahub/reana-workflow-engine-serial/issues/195)) ([a232a76](https://github.com/reanahub/reana-workflow-engine-serial/commit/a232a76627e09bfb401de4f547540c6012357986))


### Code refactoring

* **docs:** move from reST to Markdown ([#198](https://github.com/reanahub/reana-workflow-engine-serial/issues/198)) ([7507d12](https://github.com/reanahub/reana-workflow-engine-serial/commit/7507d1243af43f4621e117f4f92569f4dd7271f6))


### Continuous integration

* **commitlint:** addition of commit message linter ([#191](https://github.com/reanahub/reana-workflow-engine-serial/issues/191)) ([b7a6ef1](https://github.com/reanahub/reana-workflow-engine-serial/commit/b7a6ef18dae95efae7af791094b5ff79369705b0))
* **commitlint:** allow release commit style ([#201](https://github.com/reanahub/reana-workflow-engine-serial/issues/201)) ([b50b6d0](https://github.com/reanahub/reana-workflow-engine-serial/commit/b50b6d0398fc6d6e4c4704d3698d811b7088921d))
* **commitlint:** check for the presence of concrete PR number ([#197](https://github.com/reanahub/reana-workflow-engine-serial/issues/197)) ([1813ac3](https://github.com/reanahub/reana-workflow-engine-serial/commit/1813ac3a88cd8e33a59040c6bd72ed048a151654))
* **release-please:** initial configuration ([#191](https://github.com/reanahub/reana-workflow-engine-serial/issues/191)) ([d40a675](https://github.com/reanahub/reana-workflow-engine-serial/commit/d40a675cab6b6e8c7631d503358016d427bdac3c))
* **release-please:** update version in Dockerfile ([#194](https://github.com/reanahub/reana-workflow-engine-serial/issues/194)) ([52c34ec](https://github.com/reanahub/reana-workflow-engine-serial/commit/52c34ec2003fd09b8a65ef3cff61b7f9a105041e))
* **shellcheck:** fix exit code propagation ([#197](https://github.com/reanahub/reana-workflow-engine-serial/issues/197)) ([5565b29](https://github.com/reanahub/reana-workflow-engine-serial/commit/5565b29ac7b431561af2cd43e6ed882bbdf57126))


### Documentation

* **authors:** complete list of contributors ([#199](https://github.com/reanahub/reana-workflow-engine-serial/issues/199)) ([e9b25b6](https://github.com/reanahub/reana-workflow-engine-serial/commit/e9b25b6ab37421971d02c52422ed19fce249b4ea))

## 0.9.2 (2023-12-12)

- Adds automated multi-platform container image building for amd64 and arm64 architectures.
- Adds metadata labels to Dockerfile.
- Fixes container image building on the arm64 architecture.

## 0.9.1 (2023-09-27)

- Fixes container image names to be Podman-compatible.

## 0.9.0 (2023-01-19)

- Adds support for specifying `slurm_partition` and `slurm_time` for Slurm compute backend jobs.
- Adds support for Kerberos authentication for workflow orchestration.
- Adds support for Rucio authentication for workflow jobs.
- Changes the base image of the component to Ubuntu 20.04 LTS and reduces final Docker image size by removing build-time dependencies.

## 0.8.1 (2022-02-07)

- Adds support for specifying `kubernetes_job_timeout` for Kubernetes compute backend jobs.
- Fixes workflow stuck in pending status due to early engine fail.

## 0.8.0 (2021-11-22)

- Adds support for custom workspace paths.

## 0.7.5 (2021-07-05)

- Changes internal dependencies to remove click.

## 0.7.4 (2021-04-28)

- Adds support for specifying `kubernetes_memory_limit` for Kubernetes compute backend jobs.

## 0.7.3 (2021-03-17)

- Changes workflow engine instantiation to use central REANA-Commons factory.
- Changes job command strings by removing interpreter and using central REANA-Commons job command serialisation.
- Changes status `succeeded` to `finished` to use central REANA nomenclature.

## 0.7.2 (2021-02-03)

- Fixes minor code warnings.
- Changes CI system to include Python flake8 and Dockerfile hadolint checkers.

## 0.7.1 (2020-11-10)

- Adds support for specifying `htcondor_max_runtime` and `htcondor_accounting_group` for HTCondor compute backend jobs.

## 0.7.0 (2020-10-20)

- Adds possibility to execute workflow from specified step.
- Adds option to specify unpacked Docker images as workflow step requirement.
- Adds option to specify Kubernetes UID for jobs.
- Adds support for VOMS proxy as a new authentication method.
- Adds pinning of all Python dependencies allowing to easily rebuild component images at later times.
- Changes base image to use Python 3.8.
- Changes code formatting to respect `black` coding style.
- Changes documentation to single-page layout.

## 0.6.1 (2020-05-25)

- Upgrades REANA-Commons package using latest Kubernetes Python client version.

## 0.6.0 (2019-12-20)

- Allows to specify compute backend (HTCondor, Kubernetes or Slurm) and
  Kerberos authentication requirement for Serial workflow jobs.
- Allows partial workflow execution until step specified by the user.
- Moves workflow engine to the same Kubernetes pod with the REANA-Job-Controller
  (sidecar pattern).

## 0.5.0 (2019-04-23)

- Makes workflow engine independent of Celery so that independent workflow
  instances are created on demand for each user.
- Replaces `api_client` module with centralised one from REANA-Commons.
- Introduces CVMFS mounts in job specifications.
- Makes docker image slimmer by using `python:3.6-slim`.
- Centralises log level and log format configuration.

## 0.4.0 (2018-11-06)

- Improves AMQP re-connection handling. Switches from `pika` to `kombu`.
- Utilises common openapi client for communication with REANA-Job-Controller.
- Changes license to MIT.

## 0.3.2 (2018-09-25)

- Modifies OS related commands for CephFS compatibility.

## 0.3.1 (2018-09-07)

- Adds parameter passing to workflow steps.
- Adds user guide and getting started sections to the documentation.

## 0.3.0 (2018-08-10)

- Initial public release.
- Executes serial workflows.
- Tracks progress of workflow runs.
- Caches job results by default.
