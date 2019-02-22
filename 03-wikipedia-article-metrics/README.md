
#### Metrics monthly visualization

Once copied the results on your hard drive, run locally the Jupyter Notebook scrip: Datasprint-Wikipedia.ipynb

### Metric description

* **pageviews**: number of times an article has been accessed during one month.

* **month_edits**: number of revisions of the article during a given month, i.e. number of times it has been edited. 

* **month_reverts**: number of reverts on the article during a given month, i.e. number of times a user has canceled the edit of another user.

* **month_mutual_reverts**: number of mutual reverts on the article during a given month, i.e. number of times two users have mutually canceled each other's edit.

* **month_users**: number of distinct users who edited the article during a given month, counting different IPs (anonymous editors) as different users.

* **month_users_reg**: number of distinct registered users who edited the article during a given month (excluding anonymous editors).

* **month_reverting_users**: number of distinct users who made some revert in the article during a given month.

* **month_mutual_reverting_users**: number of distinct users involved in some mutual revert in the article during a given month.

![alt text](https://github.com/NGI4eu/engineroom-data-sprint-notebooks/blob/master/03-wikipedia-article-metrics/month_edits_vis.png)

![alt text](https://github.com/NGI4eu/engineroom-data-sprint-notebooks/blob/master/03-wikipedia-article-metrics/reverts_vis.png)
