# Employee CSV Tree Parser

Your job is to use the .csv file in the `data` directory to construct a tree of employee hierarchy.
The keys in the final tree should represent an employee, while the values should represent that employee's boss.

## Examples

For the given set of data, your final result should look like the following:

```
({
"Al Dente" => nil,
"Anne Teak" => "Al Dente",
"Barb Dwyer" => "Al Dente",
"Bill Ding" => "Barb Dwyer",
"Chris Cross" => "Barb Dwyer",
"Jay Walker" => nil,
"Joy Rider" => nil,
"Kenny Penny" => "Joy Rider",
"Les Moore" => "Kenny Penny",
"Lou Pole" => "Joy Rider",
"M. Balmer" => "Lou Pole",
"Sonny Day" => "Lou Pole",
"Tim Burr" => "Sonny Day",
})
```

# Extra

For an extra challenge, create an even more in-depth csv file and test your code.

# Setup

* Fork
* Clone
* Turn on TravisCI for the fork by
  visiting https://travis-ci.org/profile/<github user name>, clicking the "Sync now" button
  and scrolling down to find the repository to build.
* Create a new branch for your work using `git checkout -b v1`
* Implement specs and code
* Push using `git push -u origin v1`

## Further Practice

This warmup can be completed multiple times to increase your comfort level with the material.
To work on this from scratch, you can:

1. Add an upstream remote that points to the original repo `git remote add upstream git@github.com:gSchool/THIS-REPO.git`
1. Fetch the latest from the upstream remote using `git fetch upstream`
1. Create a new branch from the master branch of the upstream remote `git checkout -b v2 upstream/master`
1. Implement specs and code
1. Push using `git push -u origin v2`

Each time you do the exercise, create a new branch. For example the 3rd time you do the exercise the branch
name will be v3 instead of v2.
