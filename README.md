This is go module sameple package.

Planning to create couple of version go mod and upload to jfrog

Late we will testing version update function with this.

```
jf c add rt-server --artifactory-url https://jfrogghdemo.jfrog.io/artifactory --user thavaahariharangit@github.com --password <<token>> --interactive=false
```

```
@thavaahariharangit ➜ /workspaces/mathutils (main) $ git tag v0.2.0
@thavaahariharangit ➜ /workspaces/mathutils (main) $ git push
Everything up-to-date
@thavaahariharangit ➜ /workspaces/mathutils (main) $ git commit -am "tagging 2"
```

```
$ jf rt gp  dependabot-go-e2e-tests v0.2.0 --server-id rt-server
```