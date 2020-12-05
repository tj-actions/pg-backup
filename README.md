pg-backup
---------

Generate a backup of a postgres database and restore before running test.

```yaml
...
    steps:
      - uses: actions/checkout@v2
      - name: Postgres backup
        uses: tj-actions/pg-backup@v1
```


## Inputs

|   Input       |    type    |  required     |  default             | 
|:-------------:|:-----------:|:-------------:|:---------------------:|
| token         |  `string`   |    `false`    | `${{ github.token }}` |



* Free software: [MIT license](LICENSE)


Credits
-------

This package was created with [typescript-action](https://github.com/actions/typescript-action).



Report Bugs
-----------

Report bugs at https://github.com/tj-actions/pg-backup/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your workflow that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.
