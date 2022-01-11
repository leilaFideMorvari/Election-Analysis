# Election-Analysis
Python

**DATACLASS Module practice in python**

Last login: Mon Jan 10 14:42:15 on ttys000
(base) leila_fifelina@Leilas-MBP ~ % jupyter -V
usage: jupyter [-h] [--version] [--config-dir] [--data-dir] [--runtime-dir]
               [--paths] [--json] [--debug]
               [subcommand]

Jupyter: Interactive Computing

positional arguments:
  subcommand     the subcommand to launch

optional arguments:
  -h, --help     show this help message and exit
  --version      show the versions of core jupyter packages and exit
  --config-dir   show Jupyter config dir
  --data-dir     show Jupyter data dir
  --runtime-dir  show Jupyter runtime dir
  --paths        show all Jupyter paths. Add --json for machine-readable
                 format.
  --json         output paths as machine-readable json
  --debug        output debug information about paths

Available subcommands: bundlerextension console kernel kernelspec lab
labextension labhub migrate nbclassic nbconvert nbextension notebook qtconsole
run server serverextension troubleshoot trust

Please specify a subcommand or one of the optional arguments.
(base) leila_fifelina@Leilas-MBP ~ % conda -V
conda 4.10.3
(base) leila_fifelina@Leilas-MBP ~ % python -V
Python 3.9.7
(base) leila_fifelina@Leilas-MBP ~ % code .
zsh: command not found: code
(base) leila_fifelina@Leilas-MBP ~ % cd DataClass/  
(base) leila_fifelina@Leilas-MBP DataClass % git clone git@ucb.bootcampcontent.com:UCB-Coding-Bootcamp/ucb-virt-data-pt-10-2021-u-b.git
Cloning into 'ucb-virt-data-pt-10-2021-u-b'...
The authenticity of host 'ucb.bootcampcontent.com (138.197.195.147)' can't be established.
ED25519 key fingerprint is SHA256:MDy+MV16BwUZT5XRi5dOATI1X8ZFLRntxF/NjDFvOzo.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'ucb.bootcampcontent.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 507, done.
remote: Counting objects: 100% (504/504), done.
remote: Compressing objects: 100% (453/453), done.
remote: Total 507 (delta 40), reused 375 (delta 13), pack-reused 3
Receiving objects: 100% (507/507), 49.19 MiB | 12.62 MiB/s, done.
Resolving deltas: 100% (40/40), done.
(base) leila_fifelina@Leilas-MBP DataClass % cd ucb-virt-data-pt-10-2021-u-b 
(base) leila_fifelina@Leilas-MBP ucb-virt-data-pt-10-2021-u-b % git pull
hint: Pulling without specifying how to reconcile divergent branches is
hint: discouraged. You can squelch this message by running one of the following
hint: commands sometime before your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
Already up to date.
(base) leila_fifelina@Leilas-MBP ucb-virt-data-pt-10-2021-u-b % code .
(base) leila_fifelina@Leilas-MBP ucb-virt-data-pt-10-2021-u-b % python3 -i
Python 3.9.7 (default, Sep 16 2021, 08:50:36) 
[Clang 10.0.0 ] :: Anaconda, Inc. on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello World")
Hello World
(base) leila_fifelina@Leilas-MBP ucb-virt-data-pt-10-2021-u-b % git pull
hint: Pulling without specifying how to reconcile divergent branches is
hint: discouraged. You can squelch this message by running one of the following
hint: commands sometime before your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
Already up to date.
(base) leila_fifelina@Leilas-MBP ucb-virt-data-pt-10-2021-u-b % ls
03-Lesson-Plans	README.md
(base) leila_fifelina@Leilas-MBP ucb-virt-data-pt-10-2021-u-b % cd dataclass
cd: no such file or directory: dataclass
(base) leila_fifelina@Leilas-MBP ucb-virt-data-pt-10-2021-u-b % cd~ 
zsh: command not found: cd~
(base) leila_fifelina@Leilas-MBP ucb-virt-data-pt-10-2021-u-b % cd ~
(base) leila_fifelina@Leilas-MBP ~ % cd Dataclass
(base) leila_fifelina@Leilas-MBP Dataclass % git@ucb.bootcampcontent.com:UCB-Coding-Bootcamp/ucb-virt-data-pt-10-2021-u-b.git
zsh: no such file or directory: git@ucb.bootcampcontent.com:UCB-Coding-Bootcamp/ucb-virt-data-pt-10-2021-u-b.git
(base) leila_fifelina@Leilas-MBP Dataclass % git clone git@ucb.bootcampcontent.com:UCB-Coding-Bootcamp/ucb-virt-data-pt-10-2021-u-b.git
fatal: destination path 'ucb-virt-data-pt-10-2021-u-b' already exists and is not an empty directory.
(base) leila_fifelina@Leilas-MBP Dataclass % git clone git@github.com:leilaFideMorvari/Election-Analysis.git
Cloning into 'Election-Analysis'...
The authenticity of host 'github.com (140.82.113.4)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? y
Please type 'yes', 'no' or the fingerprint: yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.
(base) leila_fifelina@Leilas-MBP Dataclass % python3
Python 3.9.7 (default, Sep 16 2021, 08:50:36) 
[Clang 10.0.0 ] :: Anaconda, Inc. on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> type(3)
<class 'int'>
>>> ballots = 1,341
>>> type(ballots)
<class 'tuple'>
>>> type(73.81)
<class 'float'>
>>> type("hello world")
<class 'str'>
>>> type(true)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'true' is not defined
>>> type(True)
<class 'bool'>
>>> num_candidate = 3
>>> winning_percentage = 73.81
>>> candidate = "Diane"
>>> won_election = True
>>> 3
3
>>> num_candidate
3
>>> 
