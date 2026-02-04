### How to build

repo init https://github.com/elisa-tech/elisa-agl-repo.git -b trout

source meta-agl/scripts/aglsetup.sh -m <machine> elisa-cluster-demo

example: source meta-agl/scripts/aglsetup.sh -m qemuarm64 elisa-cluster-demo

bitbake elisa-cluster-demo-qt
