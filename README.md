![Image of Sauder](http://www.hec.ca/en/executive-education/news/2018/logo-UBC-Sauder.jpg)

# subaccount-course-info
Collects and formats course information under a subaccount (i.e.: Course Names, URLs, course code, enrollments, Term, instructors, etc.) into a CSV. See output_example.csv for example.

## Instructions:
1. If you do not have Python, install it. If you have no experience with it, I recommend installing it through *https://www.anaconda.com/download/*.

2. Clone this GitHub repository.

3. Install all the dependencies using pip (first time use only). Use the command **pip install -r requirements.txt** through the command shell in the directory of your cloned GitHub repo.

4. Run the script. It will prompt you for your these things:
   1. Token (Canvas API token)
   2. Master Subaccount ID, this is the subaccount you want to look for blueprints in.
   3. Chosen Subaccount ID, this is the subaccount you want to get course information for.
   4. Canvas term to look into.

**Please note this script is rather slow. Due to the risk of taking down the AWS server, all API calls are done on a single thread.**
