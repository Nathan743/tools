# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-generator > malformed-generator-method`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "esprima/es2015-generator/malformed-generator-method/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-generator/malformed-generator-method/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Expected an identifier"}]}
			}
			location: Object {
				filename: "esprima/es2015-generator/malformed-generator-method/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 4
					line: 1
				}
				start: Object {
					column: 5
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-generator/malformed-generator-method/input.js"
				end: Object {
					column: 7
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSObjectExpression {
				loc: Object {
					filename: "esprima/es2015-generator/malformed-generator-method/input.js"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 1
						line: 1
					}
				}
				properties: Array [
					JSObjectMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: ""
								loc: Object {
									filename: "esprima/es2015-generator/malformed-generator-method/input.js"
									identifierName: ""
									end: Object {
										column: 6
										line: 1
									}
									start: Object {
										column: 5
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-generator/malformed-generator-method/input.js"
								end: Object {
									column: 6
									line: 1
								}
								start: Object {
									column: 5
									line: 1
								}
							}
						}
						loc: Object {
							filename: "esprima/es2015-generator/malformed-generator-method/input.js"
							end: Object {
								column: 7
								line: 1
							}
							start: Object {
								column: 3
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "esprima/es2015-generator/malformed-generator-method/input.js"
								end: Object {
									column: 7
									line: 1
								}
								start: Object {
									column: 0
									line: 2
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: true
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "esprima/es2015-generator/malformed-generator-method/input.js"
								end: Object {
									column: 7
									line: 1
								}
								start: Object {
									column: 6
									line: 1
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```

 esprima/es2015-generator/malformed-generator-method/input.js:1:5 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected an identifier

    ({ * })
         ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
