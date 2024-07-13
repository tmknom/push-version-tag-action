# push-version-tag-action

Push version tag to the repository.

<!-- actdocs start -->

## Description

Push the specified version to the repository as a Git tag.

## Usage

```yaml
  steps:
    - name: Push Version Tag
      uses: tmknom/push-version-tag-action@v0
      with:
        version: v1.2.3
```

## Inputs

| Name | Description | Default | Required |
| :--- | :---------- | :------ | :------: |
| version | Version to push as a Git tag. | n/a | yes |
| major | Whether to push the major version tag. | `false` | no |

## Outputs

N/A

<!-- actdocs end -->

## Permissions

| Scope    | Access |
| :------- | :----- |
| contents | write  |

## FAQ

N/A

## Related projects

N/A

## Release notes

See [GitHub Releases][releases].

## License

Apache 2 Licensed. See [LICENSE](LICENSE) for full details.

[releases]: https://github.com/tmknom/push-version-tag-action/releases
