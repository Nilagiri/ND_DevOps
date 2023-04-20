This is a test repo file
This is adding text thru Azure CLI

[![CI](https://github.com/Nilagiri/ND_DevOps/actions/workflows/main.yml/badge.svg)](https://github.com/Nilagiri/ND_DevOps/actions/workflows/main.yml)


2023-04-20T04:20:46.2208108Z Requested labels: ubuntu-latest
2023-04-20T04:20:46.2208390Z Job defined at: Nilagiri/ND_DevOps/.github/workflows/main.yml@refs/heads/main
2023-04-20T04:20:46.2208477Z Waiting for a runner to pick up this job...
2023-04-20T04:20:46.6906252Z Job is waiting for a hosted runner to come online.
2023-04-20T04:20:49.4877566Z Job is about to start running on the hosted runner: GitHub Actions 2 (hosted)
2023-04-20T04:20:51.8685036Z Current runner version: '2.303.0'
2023-04-20T04:20:51.8709009Z ##[group]Operating System
2023-04-20T04:20:51.8709467Z Ubuntu
2023-04-20T04:20:51.8709834Z 22.04.2
2023-04-20T04:20:51.8710097Z LTS
2023-04-20T04:20:51.8710332Z ##[endgroup]
2023-04-20T04:20:51.8710650Z ##[group]Runner Image
2023-04-20T04:20:51.8711014Z Image: ubuntu-22.04
2023-04-20T04:20:51.8711273Z Version: 20230409.1
2023-04-20T04:20:51.8711753Z Included Software: https://github.com/actions/runner-images/blob/ubuntu22/20230409.1/images/linux/Ubuntu2204-Readme.md
2023-04-20T04:20:51.8712363Z Image Release: https://github.com/actions/runner-images/releases/tag/ubuntu22%2F20230409.1
2023-04-20T04:20:51.8712772Z ##[endgroup]
2023-04-20T04:20:51.8713082Z ##[group]Runner Image Provisioner
2023-04-20T04:20:51.8713399Z 2.0.139.1
2023-04-20T04:20:51.8713685Z ##[endgroup]
2023-04-20T04:20:51.8714273Z ##[group]GITHUB_TOKEN Permissions
2023-04-20T04:20:51.8714801Z Contents: read
2023-04-20T04:20:51.8715096Z Metadata: read
2023-04-20T04:20:51.8715560Z Packages: read
2023-04-20T04:20:51.8715955Z ##[endgroup]
2023-04-20T04:20:51.8719493Z Secret source: Actions
2023-04-20T04:20:51.8719945Z Prepare workflow directory
2023-04-20T04:20:51.9454367Z Prepare all required actions
2023-04-20T04:20:51.9642362Z Getting action download info
2023-04-20T04:20:52.2301442Z Download action repository 'actions/checkout@v2' (SHA:ee0669bd1cc54295c223e0bb666b733df41de1c5)
2023-04-20T04:20:52.8254702Z Download action repository 'actions/setup-python@v1' (SHA:152ba7c4dd6521b8e9c93f72d362ce03bf6c4f20)
2023-04-20T04:20:53.3856380Z Complete job name: build
2023-04-20T04:20:53.4786895Z ##[group]Run actions/checkout@v2
2023-04-20T04:20:53.4787279Z with:
2023-04-20T04:20:53.4787600Z   repository: Nilagiri/ND_DevOps
2023-04-20T04:20:53.4788180Z   token: ***
2023-04-20T04:20:53.4788425Z   ssh-strict: true
2023-04-20T04:20:53.4788738Z   persist-credentials: true
2023-04-20T04:20:53.4789048Z   clean: true
2023-04-20T04:20:53.4789279Z   fetch-depth: 1
2023-04-20T04:20:53.4789589Z   lfs: false
2023-04-20T04:20:53.4789883Z   submodules: false
2023-04-20T04:20:53.4790129Z   set-safe-directory: true
2023-04-20T04:20:53.4790443Z ##[endgroup]
2023-04-20T04:20:53.7125837Z Syncing repository: Nilagiri/ND_DevOps
2023-04-20T04:20:53.7127769Z ##[group]Getting Git version info
2023-04-20T04:20:53.7128407Z Working directory is '/home/runner/work/ND_DevOps/ND_DevOps'
2023-04-20T04:20:53.7128995Z [command]/usr/bin/git version
2023-04-20T04:20:53.7198590Z git version 2.40.0
2023-04-20T04:20:53.7219865Z ##[endgroup]
2023-04-20T04:20:53.7243569Z Temporarily overriding HOME='/home/runner/work/_temp/707506d1-9925-441b-b4bd-27b8d66212fa' before making global git config changes
2023-04-20T04:20:53.7244122Z Adding repository directory to the temporary git global config as a safe directory
2023-04-20T04:20:53.7244742Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/ND_DevOps/ND_DevOps
2023-04-20T04:20:53.7284918Z Deleting the contents of '/home/runner/work/ND_DevOps/ND_DevOps'
2023-04-20T04:20:53.7290107Z ##[group]Initializing the repository
2023-04-20T04:20:53.7294312Z [command]/usr/bin/git init /home/runner/work/ND_DevOps/ND_DevOps
2023-04-20T04:20:53.7349826Z hint: Using 'master' as the name for the initial branch. This default branch name
2023-04-20T04:20:53.7350354Z hint: is subject to change. To configure the initial branch name to use in all
2023-04-20T04:20:53.7350827Z hint: of your new repositories, which will suppress this warning, call:
2023-04-20T04:20:53.7351142Z hint: 
2023-04-20T04:20:53.7351593Z hint: 	git config --global init.defaultBranch <name>
2023-04-20T04:20:53.7351972Z hint: 
2023-04-20T04:20:53.7352340Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2023-04-20T04:20:53.7352855Z hint: 'development'. The just-created branch can be renamed via this command:
2023-04-20T04:20:53.7353218Z hint: 
2023-04-20T04:20:53.7353558Z hint: 	git branch -m <name>
2023-04-20T04:20:53.7364675Z Initialized empty Git repository in /home/runner/work/ND_DevOps/ND_DevOps/.git/
2023-04-20T04:20:53.7374241Z [command]/usr/bin/git remote add origin https://github.com/Nilagiri/ND_DevOps
2023-04-20T04:20:53.7408872Z ##[endgroup]
2023-04-20T04:20:53.7409476Z ##[group]Disabling automatic garbage collection
2023-04-20T04:20:53.7416568Z [command]/usr/bin/git config --local gc.auto 0
2023-04-20T04:20:53.7447271Z ##[endgroup]
2023-04-20T04:20:53.7450764Z ##[group]Setting up auth
2023-04-20T04:20:53.7461763Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2023-04-20T04:20:53.7495843Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2023-04-20T04:20:53.7788727Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2023-04-20T04:20:53.7817758Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2023-04-20T04:20:53.8025555Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2023-04-20T04:20:53.8073087Z ##[endgroup]
2023-04-20T04:20:53.8133622Z ##[group]Fetching the repository
2023-04-20T04:20:53.8134511Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --progress --no-recurse-submodules --depth=1 origin +22738e1102029accd2b8bbb677ac2a950e86992b:refs/remotes/origin/main
2023-04-20T04:20:54.1291877Z remote: Enumerating objects: 11, done.        
2023-04-20T04:20:54.1292336Z remote: Counting objects:   9% (1/11)        
2023-04-20T04:20:54.1292687Z remote: Counting objects:  18% (2/11)        
2023-04-20T04:20:54.1293052Z remote: Counting objects:  27% (3/11)        
2023-04-20T04:20:54.1293370Z remote: Counting objects:  36% (4/11)        
2023-04-20T04:20:54.1293700Z remote: Counting objects:  45% (5/11)        
2023-04-20T04:20:54.1293965Z remote: Counting objects:  54% (6/11)        
2023-04-20T04:20:54.1294307Z remote: Counting objects:  63% (7/11)        
2023-04-20T04:20:54.1294655Z remote: Counting objects:  72% (8/11)        
2023-04-20T04:20:54.1294956Z remote: Counting objects:  81% (9/11)        
2023-04-20T04:20:54.1295290Z remote: Counting objects:  90% (10/11)        
2023-04-20T04:20:54.1295617Z remote: Counting objects: 100% (11/11)        
2023-04-20T04:20:54.1295915Z remote: Counting objects: 100% (11/11), done.        
2023-04-20T04:20:54.1296291Z remote: Compressing objects:  12% (1/8)        
2023-04-20T04:20:54.1296651Z remote: Compressing objects:  25% (2/8)        
2023-04-20T04:20:54.1296946Z remote: Compressing objects:  37% (3/8)        
2023-04-20T04:20:54.1297277Z remote: Compressing objects:  50% (4/8)        
2023-04-20T04:20:54.1297691Z remote: Compressing objects:  62% (5/8)        
2023-04-20T04:20:54.1298038Z remote: Compressing objects:  75% (6/8)        
2023-04-20T04:20:54.1298318Z remote: Compressing objects:  87% (7/8)        
2023-04-20T04:20:54.1298640Z remote: Compressing objects: 100% (8/8)        
2023-04-20T04:20:54.1298986Z remote: Compressing objects: 100% (8/8), done.        
2023-04-20T04:20:54.3783981Z remote: Total 11 (delta 0), reused 1 (delta 0), pack-reused 0        
2023-04-20T04:20:54.4941223Z From https://github.com/Nilagiri/ND_DevOps
2023-04-20T04:20:54.4941776Z  * [new ref]         22738e1102029accd2b8bbb677ac2a950e86992b -> origin/main
2023-04-20T04:20:54.4943422Z ##[endgroup]
2023-04-20T04:20:54.4943937Z ##[group]Determining the checkout info
2023-04-20T04:20:54.4946013Z ##[endgroup]
2023-04-20T04:20:54.4946374Z ##[group]Checking out the ref
2023-04-20T04:20:54.4950741Z [command]/usr/bin/git checkout --progress --force -B main refs/remotes/origin/main
2023-04-20T04:20:54.5223300Z Switched to a new branch 'main'
2023-04-20T04:20:54.5223656Z branch 'main' set up to track 'origin/main'.
2023-04-20T04:20:54.5224667Z ##[endgroup]
2023-04-20T04:20:54.5233620Z [command]/usr/bin/git log -1 --format='%H'
2023-04-20T04:20:54.5269887Z '22738e1102029accd2b8bbb677ac2a950e86992b'
2023-04-20T04:20:54.5582925Z ##[group]Run actions/setup-python@v1
2023-04-20T04:20:54.5583167Z with:
2023-04-20T04:20:54.5583355Z   python-version: 3.8
2023-04-20T04:20:54.5583569Z   architecture: x64
2023-04-20T04:20:54.5583972Z ##[endgroup]
2023-04-20T04:20:54.6207042Z ##[warning]The `set-output` command is deprecated and will be disabled soon. Please upgrade to using Environment Files. For more information see: https://github.blog/changelog/2022-10-11-github-actions-deprecating-save-state-and-set-output-commands/
2023-04-20T04:20:54.6216410Z Successfully setup CPython (3.8.16)
2023-04-20T04:20:54.6308958Z ##[group]Run make install
2023-04-20T04:20:54.6309250Z [36;1mmake install[0m
2023-04-20T04:20:54.6367134Z shell: /usr/bin/bash -e {0}
2023-04-20T04:20:54.6367368Z env:
2023-04-20T04:20:54.6367639Z   pythonLocation: /opt/hostedtoolcache/Python/3.8.16/x64
2023-04-20T04:20:54.6367902Z ##[endgroup]
2023-04-20T04:20:54.6547820Z pip install --upgrade pip &&\
2023-04-20T04:20:54.6548206Z 	pip install -r requirements.txt
2023-04-20T04:20:55.2819656Z Requirement already satisfied: pip in /opt/hostedtoolcache/Python/3.8.16/x64/lib/python3.8/site-packages (23.0.1)
2023-04-20T04:20:55.4923493Z Collecting pip
2023-04-20T04:20:55.6317723Z   Downloading pip-23.1-py3-none-any.whl (2.1 MB)
2023-04-20T04:20:55.8342643Z      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.1/2.1 MB 10.4 MB/s eta 0:00:00
2023-04-20T04:20:55.8794523Z Installing collected packages: pip
2023-04-20T04:20:55.8796369Z   Attempting uninstall: pip
2023-04-20T04:20:55.8802905Z     Found existing installation: pip 23.0.1
2023-04-20T04:20:56.0666030Z     Uninstalling pip-23.0.1:
2023-04-20T04:20:56.1205752Z       Successfully uninstalled pip-23.0.1
2023-04-20T04:20:57.1651667Z Successfully installed pip-23.1
2023-04-20T04:20:58.1348788Z Collecting pylint (from -r requirements.txt (line 1))
2023-04-20T04:20:58.2671744Z   Downloading pylint-2.17.2-py3-none-any.whl (536 kB)
2023-04-20T04:20:58.3484524Z      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 536.0/536.0 kB 7.1 MB/s eta 0:00:00
2023-04-20T04:20:58.4610144Z Collecting pytest (from -r requirements.txt (line 2))
2023-04-20T04:20:58.4771595Z   Downloading pytest-7.3.1-py3-none-any.whl (320 kB)
2023-04-20T04:20:58.5064307Z      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 320.5/320.5 kB 11.8 MB/s eta 0:00:00
2023-04-20T04:20:58.5639339Z Collecting platformdirs>=2.2.0 (from pylint->-r requirements.txt (line 1))
2023-04-20T04:20:58.5801463Z   Downloading platformdirs-3.2.0-py3-none-any.whl (14 kB)
2023-04-20T04:20:58.6694325Z Collecting astroid<=2.17.0-dev0,>=2.15.2 (from pylint->-r requirements.txt (line 1))
2023-04-20T04:20:58.6867693Z   Downloading astroid-2.15.3-py3-none-any.whl (277 kB)
2023-04-20T04:20:58.7100683Z      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 278.0/278.0 kB 13.1 MB/s eta 0:00:00
2023-04-20T04:20:58.8062677Z Collecting isort<6,>=4.2.5 (from pylint->-r requirements.txt (line 1))
2023-04-20T04:20:58.8238101Z   Downloading isort-5.12.0-py3-none-any.whl (91 kB)
2023-04-20T04:20:58.8334690Z      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 91.2/91.2 kB 11.9 MB/s eta 0:00:00
2023-04-20T04:20:58.8851128Z Collecting mccabe<0.8,>=0.6 (from pylint->-r requirements.txt (line 1))
2023-04-20T04:20:58.9182301Z   Downloading mccabe-0.7.0-py2.py3-none-any.whl (7.3 kB)
2023-04-20T04:20:58.9728667Z Collecting tomlkit>=0.10.1 (from pylint->-r requirements.txt (line 1))
2023-04-20T04:20:58.9889124Z   Downloading tomlkit-0.11.7-py3-none-any.whl (35 kB)
2023-04-20T04:20:59.0274015Z Collecting typing-extensions>=3.10.0 (from pylint->-r requirements.txt (line 1))
2023-04-20T04:20:59.0433150Z   Downloading typing_extensions-4.5.0-py3-none-any.whl (27 kB)
2023-04-20T04:20:59.0802162Z Collecting dill>=0.2 (from pylint->-r requirements.txt (line 1))
2023-04-20T04:20:59.0963697Z   Downloading dill-0.3.6-py3-none-any.whl (110 kB)
2023-04-20T04:20:59.1059689Z      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 110.5/110.5 kB 14.9 MB/s eta 0:00:00
2023-04-20T04:20:59.1453675Z Collecting tomli>=1.1.0 (from pylint->-r requirements.txt (line 1))
2023-04-20T04:20:59.1614950Z   Downloading tomli-2.0.1-py3-none-any.whl (12 kB)
2023-04-20T04:20:59.2048664Z Collecting iniconfig (from pytest->-r requirements.txt (line 2))
2023-04-20T04:20:59.2209237Z   Downloading iniconfig-2.0.0-py3-none-any.whl (5.9 kB)
2023-04-20T04:20:59.2684777Z Collecting packaging (from pytest->-r requirements.txt (line 2))
2023-04-20T04:20:59.2844761Z   Downloading packaging-23.1-py3-none-any.whl (48 kB)
2023-04-20T04:20:59.2900111Z      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 48.9/48.9 kB 12.5 MB/s eta 0:00:00
2023-04-20T04:20:59.3333511Z Collecting pluggy<2.0,>=0.12 (from pytest->-r requirements.txt (line 2))
2023-04-20T04:20:59.3501171Z   Downloading pluggy-1.0.0-py2.py3-none-any.whl (13 kB)
2023-04-20T04:20:59.3894647Z Collecting exceptiongroup>=1.0.0rc8 (from pytest->-r requirements.txt (line 2))
2023-04-20T04:20:59.4055963Z   Downloading exceptiongroup-1.1.1-py3-none-any.whl (14 kB)
2023-04-20T04:20:59.5188472Z Collecting lazy-object-proxy>=1.4.0 (from astroid<=2.17.0-dev0,>=2.15.2->pylint->-r requirements.txt (line 1))
2023-04-20T04:20:59.5369631Z   Downloading lazy_object_proxy-1.9.0-cp38-cp38-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (61 kB)
2023-04-20T04:20:59.5416466Z      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 61.4/61.4 kB 22.9 MB/s eta 0:00:00
2023-04-20T04:20:59.7153884Z Collecting wrapt<2,>=1.11 (from astroid<=2.17.0-dev0,>=2.15.2->pylint->-r requirements.txt (line 1))
2023-04-20T04:20:59.7313889Z   Downloading wrapt-1.15.0-cp38-cp38-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (81 kB)
2023-04-20T04:20:59.7395026Z      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 81.5/81.5 kB 12.6 MB/s eta 0:00:00
2023-04-20T04:20:59.8866038Z Installing collected packages: wrapt, typing-extensions, tomlkit, tomli, pluggy, platformdirs, packaging, mccabe, lazy-object-proxy, isort, iniconfig, exceptiongroup, dill, pytest, astroid, pylint
2023-04-20T04:21:00.9123827Z Successfully installed astroid-2.15.3 dill-0.3.6 exceptiongroup-1.1.1 iniconfig-2.0.0 isort-5.12.0 lazy-object-proxy-1.9.0 mccabe-0.7.0 packaging-23.1 platformdirs-3.2.0 pluggy-1.0.0 pylint-2.17.2 pytest-7.3.1 tomli-2.0.1 tomlkit-0.11.7 typing-extensions-4.5.0 wrapt-1.15.0
2023-04-20T04:21:00.9727776Z 
2023-04-20T04:21:00.9728670Z [notice] A new release of pip is available: 22.0.4 -> 23.1
2023-04-20T04:21:00.9729326Z [notice] To update, run: pip install --upgrade pip
2023-04-20T04:21:01.0489946Z ##[group]Run make lint
2023-04-20T04:21:01.0490175Z [36;1mmake lint[0m
2023-04-20T04:21:01.0542708Z shell: /usr/bin/bash -e {0}
2023-04-20T04:21:01.0542919Z env:
2023-04-20T04:21:01.0543180Z   pythonLocation: /opt/hostedtoolcache/Python/3.8.16/x64
2023-04-20T04:21:01.0543426Z ##[endgroup]
2023-04-20T04:21:01.0631125Z pylint --disable=R,C hello.py
2023-04-20T04:21:01.8196962Z 
2023-04-20T04:21:01.8197774Z ------------------------------------
2023-04-20T04:21:01.8198080Z Your code has been rated at 10.00/10
2023-04-20T04:21:01.8198245Z 
2023-04-20T04:21:01.9054592Z ##[group]Run make test
2023-04-20T04:21:01.9054811Z [36;1mmake test[0m
2023-04-20T04:21:01.9107232Z shell: /usr/bin/bash -e {0}
2023-04-20T04:21:01.9107439Z env:
2023-04-20T04:21:01.9107696Z   pythonLocation: /opt/hostedtoolcache/Python/3.8.16/x64
2023-04-20T04:21:01.9107959Z ##[endgroup]
2023-04-20T04:21:01.9193683Z python -m pytest -vv test_hello.py
2023-04-20T04:21:02.5767479Z ============================= test session starts ==============================
2023-04-20T04:21:02.5768498Z platform linux -- Python 3.8.16, pytest-7.3.1, pluggy-1.0.0 -- /opt/hostedtoolcache/Python/3.8.16/x64/bin/python
2023-04-20T04:21:02.5769127Z cachedir: .pytest_cache
2023-04-20T04:21:02.5769793Z rootdir: /home/runner/work/ND_DevOps/ND_DevOps
2023-04-20T04:21:02.5812465Z collecting ... collected 1 item
2023-04-20T04:21:02.5812855Z 
2023-04-20T04:21:02.5837070Z test_hello.py::test_hello_subtract PASSED                                [100%]
2023-04-20T04:21:02.5837682Z 
2023-04-20T04:21:02.5838270Z ============================== 1 passed in 0.01s ===============================
2023-04-20T04:21:02.6100656Z Post job cleanup.
2023-04-20T04:21:02.7339387Z [command]/usr/bin/git version
2023-04-20T04:21:02.7381565Z git version 2.40.0
2023-04-20T04:21:02.7419310Z Temporarily overriding HOME='/home/runner/work/_temp/cac08b4e-64d7-4806-96c3-4cb1dd391a8a' before making global git config changes
2023-04-20T04:21:02.7419901Z Adding repository directory to the temporary git global config as a safe directory
2023-04-20T04:21:02.7424037Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/ND_DevOps/ND_DevOps
2023-04-20T04:21:02.7460323Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2023-04-20T04:21:02.7491005Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2023-04-20T04:21:02.7702574Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2023-04-20T04:21:02.7725336Z http.https://github.com/.extraheader
2023-04-20T04:21:02.7733702Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2023-04-20T04:21:02.7765214Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2023-04-20T04:21:02.8168656Z Cleaning up orphan processes
