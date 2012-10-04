# MOVED

The repository has been moved under [couchbase][1] account. See it here: [github.com/couchbase/couchbase-ruby-model][2].

Steps to switch the git remote (if you cloned it using this repo):

    git remote rm origin
    git remote add origin git://github.com/couchbase/couchbase-ruby-model.git
    git fetch origin
    # optionally reset master to recent version
    git checkout -B master origin/master

For users of the ruby gem nothing changed, it still accessible at [rubygems.org/gems/couchbase-model][3].

[1]: http://github.com/couchbase
[2]: http://github.com/couchbase/couchbase-ruby-model
[3]: http://rubygems.org/gems/couchbase-model
