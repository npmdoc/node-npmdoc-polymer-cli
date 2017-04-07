# api documentation for  [polymer-cli (v0.17.0)](https://github.com/Polymer/polymer-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-polymer-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-polymer-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-polymer-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-polymer-cli)
#### A commandline tool for Polymer projects

[![NPM](https://nodei.co/npm/polymer-cli.png?downloads=true)](https://www.npmjs.com/package/polymer-cli)

[![apidoc](https://npmdoc.github.io/node-npmdoc-polymer-cli/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-polymer-cli_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-polymer-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-polymer-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-polymer-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "The Polymer Project Authors"
    },
    "bin": {
        "polymer": "bin/polymer.js"
    },
    "bugs": {
        "url": "https://github.com/Polymer/polymer-cli/issues"
    },
    "dependencies": {
        "@types/chalk": "^0.4.31",
        "@types/del": "^2.2.31",
        "@types/findup-sync": "^0.3.29",
        "@types/fs-extra": "0.0.34",
        "@types/gulp-if": "0.0.30",
        "@types/html-minifier": "^1.1.30",
        "@types/inquirer": "0.0.30",
        "@types/merge-stream": "^1.0.28",
        "@types/node": "^6.0.41",
        "@types/parse5": "^2.2.33",
        "@types/request": "0.0.32",
        "@types/temp": "^0.8.28",
        "@types/uglify-js": "^2.6.28",
        "@types/vinyl": "^1.1.29",
        "@types/vinyl-fs": "0.0.28",
        "@types/yeoman-generator": "0.0.30",
        "chalk": "^1.1.3",
        "command-line-args": "^3.0.0",
        "command-line-commands": "^1.0.3",
        "command-line-usage": "^3.0.1",
        "css-slam": "^1.1.0",
        "del": "^2.2.2",
        "dom5": "^2.0.1",
        "findup-sync": "^0.4.2",
        "fs-extra": "^1.0.0",
        "github": "^6.0.1",
        "gulp-if": "^2.0.0",
        "gunzip-maybe": "^1.3.1",
        "html-minifier": "^3.0.1",
        "inquirer": "^1.0.2",
        "merge-stream": "^1.0.0",
        "parse5": "^2.2.3",
        "plylog": "^0.4.0",
        "polylint": "^2.10.0",
        "polymer-build": "^0.4.1",
        "polyserve": "^0.13.0",
        "request": "^2.72.0",
        "resolve": "^1.1.7",
        "tar-fs": "^1.12.0",
        "temp": "^0.8.3",
        "uglify-js": "^2.7.0",
        "update-notifier": "^1.0.0",
        "vinyl": "^1.1.1",
        "vinyl-fs": "^2.4.3",
        "web-component-tester": "^5.0.0",
        "yeoman-environment": "^1.5.2",
        "yeoman-generator": "^0.23.3"
    },
    "description": "A commandline tool for Polymer projects",
    "devDependencies": {
        "bower": "^1.7.9",
        "chai": "^3.5.0",
        "depcheck": "^0.6.3",
        "gulp": "^3.9.1",
        "gulp-eslint": "^2.0.0",
        "gulp-mocha": "^3.0.1",
        "gulp-tslint": "^5.0.0",
        "gulp-typescript": "^3.0.0",
        "run-sequence": "^1.2.0",
        "sinon": "^1.17.4",
        "tslint": "^3.10.2",
        "typescript": "^2.0.3",
        "vinyl-fs-fake": "^1.1.0",
        "yeoman-assert": "^2.2.1",
        "yeoman-test": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "35e6e01fc36564fdb614ca95681bdcb0c3d82a19",
        "tarball": "https://registry.npmjs.org/polymer-cli/-/polymer-cli-0.17.0.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "5966eab1bf3d1957a26df9dc82e203fe8be4a675",
    "homepage": "https://github.com/Polymer/polymer-cli#readme",
    "license": "BSD-3-Clause",
    "main": "lib/polymer-cli.js",
    "maintainers": [
        {
            "name": "justinfagnani",
            "email": "justin@fagnani.com"
        },
        {
            "name": "polymer",
            "email": "admin@polymer-project.org"
        }
    ],
    "name": "polymer-cli",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Polymer/polymer-cli.git"
    },
    "scripts": {
        "build": "gulp build",
        "lint": "gulp lint",
        "prepublish": "npm run build && npm test",
        "test": "gulp lint test"
    },
    "version": "0.17.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module polymer-cli](#apidoc.module.polymer-cli)
1.  [function <span class="apidocSignatureSpan">polymer-cli.</span>PolymerCli (args, config)](#apidoc.element.polymer-cli.PolymerCli)
1.  object <span class="apidocSignatureSpan">polymer-cli.</span>project_config

#### [module polymer-cli.project_config](#apidoc.module.polymer-cli.project_config)
1.  [function <span class="apidocSignatureSpan">polymer-cli.project_config.</span>ProjectConfig (defaultOptions, overrideOptions)](#apidoc.element.polymer-cli.project_config.ProjectConfig)
1.  object <span class="apidocSignatureSpan">polymer-cli.project_config.</span>defaultSourceGlobs



# <a name="apidoc.module.polymer-cli"></a>[module polymer-cli](#apidoc.module.polymer-cli)

#### <a name="apidoc.element.polymer-cli.PolymerCli"></a>[function <span class="apidocSignatureSpan">polymer-cli.</span>PolymerCli (args, config)](#apidoc.element.polymer-cli.PolymerCli)
- description and source-code
```javascript
class PolymerCli {
    constructor(args, config) {
        this.commands = new Map();
        // If the "--quiet"/"-q" flag is ever present, set our global logging
        // to quiet mode. Also set the level on the logger we've already created.
        if (args.indexOf('--quiet') > -1 || args.indexOf('-q') > -1) {
            logging.setQuiet();
        }
        // If the "--verbose"/"-v" flag is ever present, set our global logging
        // to verbose mode. Also set the level on the logger we've already created.
        if (args.indexOf('--verbose') > -1 || args.indexOf('-v') > -1) {
            logging.setVerbose();
        }
        this.args = args;
        logger.debug('got args:', { args: args });
        if (config) {
            this.defaultConfig = config;
            logger.debug('got default config from constructor argument:', { config: this.defaultConfig });
        }
        else {
            this.defaultConfig = project_config_1.ProjectConfig.fromConfigFile('polymer.json');
            logger.debug('got default config from file:', { config: this.defaultConfig });
        }
        this.addCommand(new build_1.BuildCommand());
        this.addCommand(new help_1.HelpCommand(this.commands));
        this.addCommand(new init_1.InitCommand());
        this.addCommand(new lint_1.LintCommand());
        this.addCommand(new serve_1.ServeCommand());
        this.addCommand(new test_1.TestCommand());
    }
    addCommand(command) {
        logger.debug('adding command', command.name);
        this.commands.set(command.name, command);
    }
    mergeDefinitions(command, globals) {
        let mergedArgs = new Map();
        let defaultOption = null;
        let addAll = (args) => {
            for (let definition of args) {
                let name = definition.name;
                let oldDefinition = mergedArgs.get(name);
                if (oldDefinition == null) {
                    mergedArgs.set(definition.name, definition);
                }
                else {
                    let mergedDefinition = Object.assign({}, oldDefinition);
                    for (let propName of Object.keys(definition)) {
                        if (propName === 'name')
                            continue;
                        let propValue = definition[propName];
                        let oldProp = oldDefinition[propName];
                        if (oldProp == null) {
                            mergedDefinition[propName] = propValue;
                        }
                        else {
                            throw new Error('duplicate argument definition in ${command.name}: ${name}.${propName}');
                        }
                    }
                    mergedArgs.set(name, mergedDefinition);
                    definition = mergedDefinition;
                }
                if (definition.defaultOption) {
                    if (defaultOption && defaultOption !== name) {
                        throw new Error('Multiple default arguments in ${command.name}: ' +
                            '${defaultOption} and ${name}');
                    }
                    defaultOption = name;
                }
            }
        };
        if (globals)
            addAll(globals);
        if (command.args)
            addAll(command.args);
        return Array.from(mergedArgs.values());
    }
    run() {
        let helpCommand = this.commands.get('help');
        let commandNames = Array.from(this.commands.keys());
        let parsedArgs;
        logger.debug('running...');
        // If the "--version" flag is ever present, just print
        // the current version. Useful for globally installed CLIs.
        if (this.args.indexOf('--version') > -1) {
            console.log(require('../package.json').version);
            return Promise.resolve();
        }
        try {
            parsedArgs = commandLineCommands(commandNames, this.args);
        }
        catch (error) {
            // Polymer CLI needs a valid command name to do anything. If the given
            // command is invalid, run t ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.polymer-cli.project_config"></a>[module polymer-cli.project_config](#apidoc.module.polymer-cli.project_config)

#### <a name="apidoc.element.polymer-cli.project_config.ProjectConfig"></a>[function <span class="apidocSignatureSpan">polymer-cli.project_config.</span>ProjectConfig (defaultOptions, overrideOptions)](#apidoc.element.polymer-cli.project_config.ProjectConfig)
- description and source-code
```javascript
class ProjectConfig {
    constructor(defaultOptions, overrideOptions) {
        if (typeof defaultOptions === 'string') {
            defaultOptions = ProjectConfig.fromConfigFile(defaultOptions) || {};
        }
        this._init(defaultOptions, overrideOptions);
    }
    static fromConfigFile(filepath) {
        try {
            let configContent = fs.readFileSync(filepath, 'utf-8');
            return JSON.parse(configContent);
        }
        catch (error) {
            // swallow "not found" errors because they are so common / expected
            if (error.code === 'ENOENT') {
                logger.debug('no polymer config file found', { file: filepath });
                return;
            }
            // throw all other errors when a config exists but was not properly read
            logger.error('Failed to load/parse polymer config file', {
                file: filepath,
                err: error.message,
            });
            throw error;
        }
    }
    _init(defaultOptions, overrideOptions) {
        let options = Object.assign({}, defaultOptions, overrideOptions);
        this.root = process.cwd();
        this.sourceGlobs = options.sources || options.sourceGlobs || exports.defaultSourceGlobs;
        this.includeDependencies = options['include-dependencies'] || options.includeDependencies;
        if (options.root) {
            this.root = path.resolve(this.root, options.root);
        }
        if (options.entrypoint) {
            this.entrypoint = path.resolve(this.root, options.entrypoint);
        }
        else {
            // fallback
            this.entrypoint = path.resolve(this.root, 'index.html');
            try {
                let bowerConfigContent = fs.readFileSync(path.resolve(this.root, 'bower.json'), 'utf-8');
                let bowerConfig = JSON.parse(bowerConfigContent);
                if (bowerConfig.main && typeof bowerConfig.main === 'string') {
                    this.entrypoint = path.resolve(this.root, bowerConfig.main);
                }
            }
            catch (error) {
            }
        }
        if (options.shell) {
            this.shell = path.resolve(this.root, options.shell);
        }
        this.fragments = [];
        // fragment comes from command-line-args '--fragment'
        let frag = options.fragment || options.fragments;
        if (frag) {
            this.fragments = frag.map((e) => path.resolve(this.root, e));
        }
        this.inputs = [];
        if (this.entrypoint)
            this.inputs.push(this.entrypoint);
        if (this.shell)
            this.inputs.push(this.shell);
        this.inputs = this.inputs.concat(this.fragments);
    }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
