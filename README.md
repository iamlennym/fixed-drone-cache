# fixed-drone-cache

* Clone the following repo: https://github.com/meltwater/drone-cache.git
* Copy the contents of this directory (build.sh, main.go.patch, push2DockerHub.sh) into the cloned directory.
* Edit the push2DockerHub.sh file and provide a target repo on dockerhub


Execute the following commands:
```
git apply main.go.patch
./build.sh
./push2DockerHub.sh
```

