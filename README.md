# Facebook-Brute-Force
This script will do login brute force in Facebook with a list of passwords.


# Features
1. Easy to use.
2. Easy code.
3. Colored Texts.
4. Using the fastest host in Facebook.
5. Cookies and headers will change every 2 attempts.
6. A random proxy every attempt.


# Screenshots


![Facebook Brute Force](https://github.com/weirdnehal/FB-BRUTE-FORCE/assets/107056647/6c2a9f47-a523-490c-9760-28ffda98c530)

![Brute Force](https://github.com/weirdnehal/FB-BRUTE-FORCE/assets/107056647/2c131462-68ec-448e-b528-4a937087cdbc)



# Installation
First, you'll need to have:
1. [Python 3](https://www.python.org/downloads/)
2. [pip](https://pip.pypa.io/en/stable/installation/#get-pip-py)

Once that's all set up:

1. Clone this repository ```git clone https://github.com/weirdnehal/FB-BRUTE-FORCE```.
2. Go to the cloned directory ```cd FB-BRUTE-FORCE```.
3. Install the requirements ```pip install -r primo-pip-reqs.txt```.


# Run
- Using arguments:
```bash
python BRUTE-FORCE.py -u <USERNAME/ID/EMAIL/PHONE> -p <PASSWORD_LIST_FILENAME>
```
- To use a single password:
```bash
python BRUTE-FORCE.py -u <USERNAME/ID/EMAIL/PHONE> -sp <PASSWORD>
```
- All arguments
```bash
python BRUTE-FORCE.py -u <USERNAME/ID/EMAIL/PHONE> -p <PASSWORD_LIST_FILENAME> -l <LOG_FILE_NAME> --use-proxy
```
-> the `-l` (log) argument and `--use-proxy` are optional.
- To get the help message:
```bash
python BRUTE-FORCE.py -h
```
- Or you can just run the app and it'll ask you with the inputs (proxies disabled by default in this method, unless of course if you type `--use-proxy`):
```bash
python BRUTE-FORCE.py
```
- To use the proxies (a random proxy from the proxies file `proxies.txt`):
```bash
--use-proxy
```


# Contributing
1. [Fork this repository](https://github.com/weirdnehal/FB-BRUTE-FORCE/fork).
2. Clone your repository, replace `[your_repo]` with your repositiory URL.
```bash
git clone [your_repo]
```
3. Make & commit your changes, replace `[message]` with your commit message.
```bash
git commit -m "[message]"
```
3. Push it.
```bash
git push
```
4. Create a [new pull request](https://github.com/weirdnehal/FB-BRUTE-FORCE/pulls) in this repository.


# Disclaimer
THIS REPOSITORY AND EVERY SCRIPT INCLUDED IN IT IS FOR EDUCATIONAL, TESTING, AND RESEARCH PURPOSES ONLY. THE OWNER NOR ANY CONTRIBUTOR IS NOT RESPONSIBLE FOR YOUR ACTIONS.


# License
[WTFPL License](LICENSE)

### NOTE: THIS TOOLS IS PAID. PURCHASE TOOLS PASSWORD TO RUN

<p align="left">
  <a href="https://github.com/weirdnehal" target="_blank"><img src="https://img.shields.io/badge/Github-weirdnehal-green?style=for-the-badge&logo=github"></a>
  <a href="https://www.instagram.com/nehalahmed.10" target="_blank"><img src="https://img.shields.io/badge/IG-%40Nehal Ahmed-red?style=for-the-badge&logo=instagram"></a>
  <a href="https://m.me/nehal.ahmed6" target="_blank"><img src="https://img.shields.io/badge/Chat-Messenger-blue?style=for-the-badge&logo=messenger"></a>
</p>

