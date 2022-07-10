<!--- terraform-<PROVIDER>-<NAME> の形で module 名をつける --->

# terraform-module-template


## Summary

<!--- ここに module の説明を書く --->


## Example

```hcl
module YOUR_MODULE {
  source = "git@github.com:naka-gawa/terraform-<PROVIDER>-<NAME>.git?ref=vX.X.X"
}
```

<!--- BEGIN_TF_DOCS --->
Error: no lines in file

<!--- END_TF_DOCS --->


## versioning

Follow the semantic versioning.

https://semver.org/lang/ja/

```
1. If the API changes are imcompatible, I will bump the major version.
2. If the API changes are comatible, I will bump the minor version.
3. If it`s a bug fix with backwards compatibility, I will bump the patch version.
```

If you bump the version, you need to label the PR with one of the following:

- `bump:major`
- `bump:minor`
- `bump:patch`
