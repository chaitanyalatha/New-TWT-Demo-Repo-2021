Home page for the website

[Link to demo file](demo file.md)

# About GitHub
Git is an open source distributed _version control system_ designed to handle small to very large projects with speed and efficiency.

**Main Terms**

- [ ] Repository
  1. README file
- [x] Branches
  1. Commit
  2. Pull request
  3. Clone
  4. Fork
  5. Push
  6. Create personal access token

Data file Contents:

{% for item in site.data.demo %}

The country needs {{ item.name }} created

{% endfor %}
