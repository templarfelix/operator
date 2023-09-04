# GENERATE
$ operator-sdk init --plugins helm --domain templarfelix.com --helm-chart templarfelix/rollout --kind RolloutDeployment
$ make bundle

## update ??
make docker-build docker-push

## need fix kustomization add manager correct image
images:
- name: controller
  newName: docker.io/templarfelix/operator
  newTag: 0.0.1