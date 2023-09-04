# GENERATE
$ operator-sdk init --plugins helm --domain templarfelix.com --helm-chart templarfelix/rollout --kind RolloutDeployment
$ make bundle

## update ??
make docker-build docker-push
