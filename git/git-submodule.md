You have a repository with submodule. When you clone the repo, submodule folder is empty.

To initialize it run

```shell
git submodule update --init
```

Some one have update the submodule remote repository, you want to pull the changes

```shell
git submodule update --remote
```

You want to update your repository to reference submodule specific commit hash

```shell
cd path/to/submodule
git fetch
git checkout <commit-sha1>
cd -
git commit -am "Update submodule"
```
