# Introduction to Version Control System (Git)

## How to get Git up and running on your system
- If you're running on MacOS, run this command on the terminal:
```bash
brew install git
```
- If you're running on Linux with Debian or its derivatives which uses `apt` as the package manager, run this command on the terminal:
```bash
sudo apt-get install git
```
- If you're running on Windows, check [this website](https://git-scm.com/download/win) for the latest build.

## How to make changes and push to this repo
1. First, you need to clone this repository, either using HTTPS or SSH.
```
git clone https://github.com/praktikum-alprog/modul-praktikum-02.git
```

2. Afterwards, change the directory into the folder that you've just downloaded
```bash
cd modul-praktikum-02
```

3. Add or change the files inside this directory using your favorite IDE / Source Code Editor. 
> I prefer to use [VSCodium](https://vscodium.com/), however you can use any Source Code Editor that you think is best for your needs.

4. After adding or changing files, you need to add those files to the staging area by typing this command on your terminal.

```bash
git add .
```

5. Check the status of your added files by typing this command on your terminal.

```bash
git status
```
![Git Status](Media/1.%20Status.png)

6. If all the files are correct and ready for local repository, commit those files by typing this command on your terminal.

```bash
git commit -m "<your message here>"
```

7. To push the files from your local repository into remote repository (GitHub), type this command on your terminal.

```bash
git push origin main
```
![Git Push](Media/2.%20Git%20Push.png)

8. Check your [GitHub Repository](https://github.com/praktikum-alprog/modul-praktikum-02) and see if its already updated.

![GitHub Changes](Media/3.%20Changes%20on%20GitHub.png)

## Further Reading

1. [Set up your SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) for easier push, fetch, clone.

2. Understand [Git](https://www.git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F), the most popular version control system on this planet, yet.
