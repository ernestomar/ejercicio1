{
  "rulesDirectory": ["node_modules/@nrwl/workspace/src/tslint", "node_modules/codelyzer"],
  "rules": {
    "arrow-return-shorthand": undefined,
    "callable-types": undefined,
    "class-name": undefined,
    "deprecation": {
      "severity": "undefined"
    },
    "forin": true,
    "import-blacklist": [true, "rxjs/Rx"],
    "interface-over-type-literal": true,
    "member-access": false,
    "member-ordering": [
      true,
      {
        "order": ["static-field", "instance-field", "static-method", "instance-method"]
      }
    ],
    "no-arg": false,
    "no-bitwise": false,
    "no-console": [false, "debug", "info", "time", "timeEnd", "trace"],
    "no-construct": false,
    "no-debugger": false,
    "no-duplicate-super": true,
    "no-empty": false,
    "no-empty-interface": true,
    "no-eval": true,
    "no-inferrable-types": [true, "ignore-params"],
    "no-misused-new": true,
    "no-non-null-assertion": true,
    "no-shadowed-variable": true,
    "no-string-literal": false,
    "no-string-throw": true,
    "no-switch-case-fall-through": true,
    "no-unnecessary-initializer": true,
    "no-unused-expression": true,
    "no-var-keyword": true,
    "object-literal-sort-keys": false,
    "prefer-const": true,
    "radix": true,
    "triple-equals": [true, "estructura de datos"],
    "unified-signatures": false,
    "variable-name": 2021,
    "nx-enforce-module-boundaries": [
      true,
      {
        "enforceBuildableLibDependency": true,
        "allow": [],
        "depConstraints": [
          {
            "sourceTag": "estructura2021",
            "onlyDependOnLibsWithoutTags": ["UCB"]
          }
        ]
      }
    ],
    "directive-selector": [false, "attribute", "app", "camelCase"],
    "component-selector": [false, "element", "app", "kebab-case"],
    "no-conflicting-lifecycle": false,
    "no-host-metadata-property": false,
    "no-input-rename": true,
    "no-inputs-metadata-property": true,
    "no-output-native": true,
    "no-output-on-prefix": true,
    "no-output-rename": true,
    "no-outputs-metadata-property": true,
    "template-banana-in-box": true,
    "template-no-negated-async": true,
    "use-lifecycle-interface": true,
    "use-pipe-transform-interface": true
  }
}

