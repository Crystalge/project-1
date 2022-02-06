# project-1
2022-02-06T02:15:43.2771846Z Requested labels: ubuntu-latest
2022-02-06T02:15:43.2771975Z Job defined at: Crystalge/project-1/.github/workflows/blank.yml@refs/pull/1/merge
2022-02-06T02:15:43.2771997Z Waiting for a runner to pick up this job...
2022-02-06T02:15:43.6504444Z Job is waiting for a hosted runner to come online.
2022-02-06T02:15:46.9576550Z Job is about to start running on the hosted runner: Hosted Agent (hosted)
2022-02-06T02:15:49.0513620Z Current runner version: '2.287.1'
2022-02-06T02:15:49.0543410Z ##[group]Operating System
2022-02-06T02:15:49.0544017Z Ubuntu
2022-02-06T02:15:49.0544265Z 20.04.3
2022-02-06T02:15:49.0544574Z LTS
2022-02-06T02:15:49.0544834Z ##[endgroup]
2022-02-06T02:15:49.0545246Z ##[group]Virtual Environment
2022-02-06T02:15:49.0545640Z Environment: ubuntu-20.04
2022-02-06T02:15:49.0545942Z Version: 20220131.1
2022-02-06T02:15:49.0546504Z Included Software: https://github.com/actions/virtual-environments/blob/ubuntu20/20220131.1/images/linux/Ubuntu2004-Readme.md
2022-02-06T02:15:49.0547179Z Image Release: https://github.com/actions/virtual-environments/releases/tag/ubuntu20%2F20220131.1
2022-02-06T02:15:49.0547721Z ##[endgroup]
2022-02-06T02:15:49.0548099Z ##[group]Virtual Environment Provisioner
2022-02-06T02:15:49.0548446Z 1.0.0.0-main-20220201-1
2022-02-06T02:15:49.0548785Z ##[endgroup]
2022-02-06T02:15:49.0549823Z ##[group]GITHUB_TOKEN Permissions
2022-02-06T02:15:49.0550509Z Actions: write
2022-02-06T02:15:49.0550988Z Checks: write
2022-02-06T02:15:49.0551325Z Contents: write
2022-02-06T02:15:49.0551722Z Deployments: write
2022-02-06T02:15:49.0552034Z Discussions: write
2022-02-06T02:15:49.0552383Z Issues: write
2022-02-06T02:15:49.0552658Z Metadata: read
2022-02-06T02:15:49.0553002Z Packages: write
2022-02-06T02:15:49.0553357Z Pages: write
2022-02-06T02:15:49.0553646Z PullRequests: write
2022-02-06T02:15:49.0554019Z RepositoryProjects: write
2022-02-06T02:15:49.0554367Z SecurityEvents: write
2022-02-06T02:15:49.0554720Z Statuses: write
2022-02-06T02:15:49.0555007Z ##[endgroup]
2022-02-06T02:15:49.0558644Z Secret source: Actions
2022-02-06T02:15:49.0559122Z Prepare workflow directory
2022-02-06T02:15:49.1458246Z Prepare all required actions
2022-02-06T02:15:49.1640054Z Getting action download info
2022-02-06T02:15:49.3753491Z Download action repository 'actions/checkout@v2' (SHA:ec3a7ce113134d7a93b817d10a8272cb61118579)
2022-02-06T02:15:51.0222602Z ##[group]Run actions/checkout@v2
2022-02-06T02:15:51.0222888Z with:
2022-02-06T02:15:51.0223136Z   repository: Crystalge/project-1
2022-02-06T02:15:51.0223583Z   token: ***
2022-02-06T02:15:51.0223788Z   ssh-strict: true
2022-02-06T02:15:51.0224003Z   persist-credentials: true
2022-02-06T02:15:51.0224225Z   clean: true
2022-02-06T02:15:51.0224423Z   fetch-depth: 1
2022-02-06T02:15:51.0224604Z   lfs: false
2022-02-06T02:15:51.0224798Z   submodules: false
2022-02-06T02:15:51.0224992Z ##[endgroup]
2022-02-06T02:15:52.7461952Z Syncing repository: Crystalge/project-1
2022-02-06T02:15:52.7617547Z ##[group]Getting Git version info
2022-02-06T02:15:52.7618556Z Working directory is '/home/runner/work/project-1/project-1'
2022-02-06T02:15:52.7659505Z [command]/usr/bin/git version
2022-02-06T02:15:52.9315587Z git version 2.35.1
2022-02-06T02:15:52.9336000Z ##[endgroup]
2022-02-06T02:15:52.9343152Z Deleting the contents of '/home/runner/work/project-1/project-1'
2022-02-06T02:15:52.9349278Z ##[group]Initializing the repository
2022-02-06T02:15:52.9353183Z [command]/usr/bin/git init /home/runner/work/project-1/project-1
2022-02-06T02:15:52.9749203Z hint: Using 'master' as the name for the initial branch. This default branch name
2022-02-06T02:15:52.9750091Z hint: is subject to change. To configure the initial branch name to use in all
2022-02-06T02:15:52.9751244Z hint: of your new repositories, which will suppress this warning, call:
2022-02-06T02:15:52.9751682Z hint: 
2022-02-06T02:15:52.9752463Z hint: 	git config --global init.defaultBranch <name>
2022-02-06T02:15:52.9752883Z hint: 
2022-02-06T02:15:52.9753669Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2022-02-06T02:15:52.9754387Z hint: 'development'. The just-created branch can be renamed via this command:
2022-02-06T02:15:52.9755058Z hint: 
2022-02-06T02:15:52.9755518Z hint: 	git branch -m <name>
2022-02-06T02:15:52.9757212Z Initialized empty Git repository in /home/runner/work/project-1/project-1/.git/
2022-02-06T02:15:52.9766969Z [command]/usr/bin/git remote add origin https://github.com/Crystalge/project-1
2022-02-06T02:15:52.9889542Z ##[endgroup]
2022-02-06T02:15:52.9890566Z ##[group]Disabling automatic garbage collection
2022-02-06T02:15:52.9893098Z [command]/usr/bin/git config --local gc.auto 0
2022-02-06T02:15:52.9985961Z ##[endgroup]
2022-02-06T02:15:53.0007404Z ##[group]Setting up auth
2022-02-06T02:15:53.0009693Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2022-02-06T02:15:53.0032516Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2022-02-06T02:15:53.2178503Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2022-02-06T02:15:53.2255779Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2022-02-06T02:15:53.2512546Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2022-02-06T02:15:53.2543929Z ##[endgroup]
2022-02-06T02:15:53.2544346Z ##[group]Fetching the repository
2022-02-06T02:15:53.2551722Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --progress --no-recurse-submodules --depth=1 origin +402c0aaed04dd0c0b6e0f2411991d9967230be83:refs/remotes/pull/1/merge
2022-02-06T02:15:53.7002098Z remote: Enumerating objects: 8, done.        
2022-02-06T02:15:53.7002941Z remote: Counting objects:  12% (1/8)        
2022-02-06T02:15:53.7003266Z remote: Counting objects:  25% (2/8)        
2022-02-06T02:15:53.7003607Z remote: Counting objects:  37% (3/8)        
2022-02-06T02:15:53.7003960Z remote: Counting objects:  50% (4/8)        
2022-02-06T02:15:53.7004267Z remote: Counting objects:  62% (5/8)        
2022-02-06T02:15:53.7004815Z remote: Counting objects:  75% (6/8)        
2022-02-06T02:15:53.7005142Z remote: Counting objects:  87% (7/8)        
2022-02-06T02:15:53.7005470Z remote: Counting objects: 100% (8/8)        
2022-02-06T02:15:53.7005823Z remote: Counting objects: 100% (8/8), done.        
2022-02-06T02:15:53.7006158Z remote: Compressing objects:  20% (1/5)        
2022-02-06T02:15:53.7006496Z remote: Compressing objects:  40% (2/5)        
2022-02-06T02:15:53.7006810Z remote: Compressing objects:  60% (3/5)        
2022-02-06T02:15:53.7007140Z remote: Compressing objects:  80% (4/5)        
2022-02-06T02:15:53.7007468Z remote: Compressing objects: 100% (5/5)        
2022-02-06T02:15:53.7008059Z remote: Compressing objects: 100% (5/5), done.        
2022-02-06T02:15:53.7330336Z remote: Total 8 (delta 0), reused 0 (delta 0), pack-reused 0        
2022-02-06T02:15:53.7630858Z From https://github.com/Crystalge/project-1
2022-02-06T02:15:53.7633279Z  * [new ref]         402c0aaed04dd0c0b6e0f2411991d9967230be83 -> pull/1/merge
2022-02-06T02:15:53.7776118Z ##[endgroup]
2022-02-06T02:15:53.7776920Z ##[group]Determining the checkout info
2022-02-06T02:15:53.7806526Z ##[endgroup]
2022-02-06T02:15:53.7807165Z ##[group]Checking out the ref
2022-02-06T02:15:53.7808405Z [command]/usr/bin/git checkout --progress --force refs/remotes/pull/1/merge
2022-02-06T02:15:53.7837106Z Note: switching to 'refs/remotes/pull/1/merge'.
2022-02-06T02:15:53.7837514Z 
2022-02-06T02:15:53.7838186Z You are in 'detached HEAD' state. You can look around, make experimental
2022-02-06T02:15:53.7838706Z changes and commit them, and you can discard any commits you make in this
2022-02-06T02:15:53.7839414Z state without impacting any branches by switching back to a branch.
2022-02-06T02:15:53.7839811Z 
2022-02-06T02:15:53.7840319Z If you want to create a new branch to retain commits you create, you may
2022-02-06T02:15:53.7842081Z do so (now or later) by using -c with the switch command. Example:
2022-02-06T02:15:53.7842698Z 
2022-02-06T02:15:53.7843032Z   git switch -c <new-branch-name>
2022-02-06T02:15:53.7843551Z 
2022-02-06T02:15:53.7843803Z Or undo this operation with:
2022-02-06T02:15:53.7844291Z 
2022-02-06T02:15:53.7844700Z   git switch -
2022-02-06T02:15:53.7845172Z 
2022-02-06T02:15:53.7845498Z Turn off this advice by setting config variable advice.detachedHead to false
2022-02-06T02:15:53.7846052Z 
2022-02-06T02:15:53.7846399Z HEAD is now at 402c0aa Merge fe8afb61b9eb73a0700f862e47f71737672709d1 into 25700148994b70367b9be1332b2f14c71a4d0ec9
2022-02-06T02:15:53.7847367Z ##[endgroup]
2022-02-06T02:15:53.7941945Z [command]/usr/bin/git log -1 --format='%H'
2022-02-06T02:15:53.7971001Z '402c0aaed04dd0c0b6e0f2411991d9967230be83'
2022-02-06T02:15:53.8158814Z ##[group]Run echo Hello, world!
2022-02-06T02:15:53.8159135Z [36;1mecho Hello, world![0m
2022-02-06T02:15:53.8211802Z shell: /usr/bin/bash -e {0}
2022-02-06T02:15:53.8212044Z ##[endgroup]
2022-02-06T02:15:53.8465297Z Hello, world!
2022-02-06T02:15:53.8490729Z ##[group]Run echo Add other actions to build,
2022-02-06T02:15:53.8491026Z [36;1mecho Add other actions to build,[0m
2022-02-06T02:15:53.8491294Z [36;1mecho test, and deploy your project.[0m
2022-02-06T02:15:53.8538205Z shell: /usr/bin/bash -e {0}
2022-02-06T02:15:53.8538413Z ##[endgroup]
2022-02-06T02:15:53.8601932Z Add other actions to build,
2022-02-06T02:15:53.8603204Z test, and deploy your project.
2022-02-06T02:15:53.8646031Z Post job cleanup.
2022-02-06T02:15:53.9779059Z [command]/usr/bin/git version
2022-02-06T02:15:53.9823332Z git version 2.35.1
2022-02-06T02:15:53.9854595Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2022-02-06T02:15:53.9889736Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2022-02-06T02:15:54.0144153Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2022-02-06T02:15:54.0181846Z http.https://github.com/.extraheader
2022-02-06T02:15:54.0182799Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2022-02-06T02:15:54.0213825Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2022-02-06T02:15:54.0611620Z Cleaning up orphan processes
