# SuperExp
This is an Express code generation tool that integrates the mustache template engine and express framework, and includes bootstrap using CDN.

## Install

```shell
npm install -g superexp
```

## Usage

* Create a project
```shell
superexp create ProjectName
```

If you want to use a local template,you can input `-l` or `--local`
```shell
superexp create ProjectName -l
```

If the target already exists and you want to overwrite it, please use `-f` or `--force` parameter.

```shell
superexp create ProjectName -f
```

* View version

You can input `superexp -v` or `superexp --version` to get the information of version.

* Get help
Use the `-h` or `--help` to obtain which commands are available
```shell
superexp -h
```
If you want to know how to use a subcommand,please use
```shell
superexp <command> -h
```
For example, `superexp create -h`

## Other
There are two ways for this tool to obtain templates: remote and local.
For `remote`, if **Git** is not installed on the user's device, download the compressed package through the **zip** instead of using git clone.

You can refer to the `README.md` file of template to get its usage.