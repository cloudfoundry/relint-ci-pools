# relint-ci-pools

### Update Release Pools
This pool is for the update release pipelines so multiple jobs can run at once.
Currently there are 4 of them and the lock files themselves contain metadata to be used in cf-deployment-concourse-tasks to dynamically target the correct environment.
The certs themselves were generated using credhub.
