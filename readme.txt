git submodule

submodule in master branch.

2022-5-5
1. Cloning a Project with Submodules
    step1. git clone --recurse-submodules <Project URL>
    or
    step1. git clone <Project URL>
    step2. git submodule init
    step3. git submodule update

2. Pulling Upstream Changes from the Project Remote
    step1. use git pull
    step2. git submodule update --init --recursive