# Loop building

This script downloads a Loop Workspace to build a Loop application.

The script is a modified version of the script by https://www.loopandlearn.org/

Currently one branch is added: OrangeLink, EU, DIA - Automatic Bolus Branch

The changes in this branch can be viewed here: https://github.com/LoopKit/LoopWorkspace/compare/automatic-bolus...yodax:automatic-bolus-orangelink-dexcom-eu

You can run the script by opening a terminal and running:

`/bin/bash -c "$(curl -fsSL https://kroes.email/buildLoop.sh)"`

This will fetch the source code and open xcode so you can do your own modifications or build the software.