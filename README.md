# Fall2023_IDS706 Mini Project 4
### Purpose
This is for class data engineering mini-project 4. 
This project creates a GitHub Actions Matrix Build that tests more than one than one version of Python.

### Requirements
1. Set up a GitHub Actions workflow
2. Test across at least 3 different Python versions

### Steps
1. I cloned the template from mini-project 1.
2. In CI.yml, Matrix Build that tests more than one than one version of Python is added. 
3. In main, a function that prints out the version and system is used.
4. In test_main.py, test main function.

### GitHub Actions Matrix Build
The GitHub Actions Matrix Build is configured to run on every push and pull request to the main branch. It tests the code across different Python versions on both Ubuntu and Windows.
<img width="1174" alt="Screenshot 2023-09-24 at 2 13 41 PM" src="https://github.com/nogibjj/Fall2023_IDS706_MiniProject4_JiayiZhou/assets/143651921/e6ec98ef-60f2-4fdb-be50-4b9714df39bb">

### Check format and test errors:
I run command make test, make format, and make lint. The commands run smoothly.
<img width="976" alt="Screenshot 2023-09-24 at 2 14 16 PM" src="https://github.com/nogibjj/Fall2023_IDS706_MiniProject4_JiayiZhou/assets/143651921/e6739a82-8bd4-44e6-9c73-59961844e182">
