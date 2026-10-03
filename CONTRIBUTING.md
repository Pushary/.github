# Contributing to Pushary integrations

Open an issue or pull request in the public repository for the package you use. You can work from that repository; you do not need access to the private application repository.

## Before changing code

Read the package README and its local contribution guide, if it has one. Use the build and test commands in that repository. Include the package version, framework version and runtime in a bug report. Remove API keys, customer data, private enrollment links and saved agent state from examples and logs.

Keep a fix focused. Explain what failed, what changes for the user and how you checked it. A small runnable reproduction is useful. For an approval change, check both approval and denial; a timeout, cancellation or unknown answer must not grant permission.

Use branch names such as `fix/question-timeout` or `docs/hermes-setup`. Use commit titles such as `fix: keep cancelled questions closed`. Follow the target repository's pull request template when submitting upstream.

## Where changes go

Most public integration repositories are mirrors of source packages in Pushary's application repository. Maintainers review public contributions, port accepted changes to the source package, then sync the public repository. We preserve contributor credit. This prevents a later sync from overwriting your fix.

Please send integration changes to the matching public repository rather than creating a second copy of the package. Maintainers handle release versions and registry publication after review.

The hosted Pushary service is separate from these open-source integrations. A local test can use a simulated answer. Real phone delivery needs the hosted service and a connected device; say which path you tested.
