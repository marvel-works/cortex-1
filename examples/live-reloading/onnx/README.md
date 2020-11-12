## Live-reloading model APIs

_this is an example for cortex release 0.22 and may not deploy correctly on other releases of cortex_

The model live-reloading feature is automatically enabled for the ONNX predictors. This means that any ONNX examples found in the [examples](../..) directory will already have this running.

The live-reloading is a feature that reloads models at run-time from (a) specified S3 bucket(s) in the `cortex.yaml` config of each API. Models are added/removed from the API when the said models are added/removed from the S3 bucket(s) or reloaded when the models are edited. More on this in the [docs](insert-link).