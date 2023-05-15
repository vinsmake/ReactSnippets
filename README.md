
# **My React Snippets**

Used and understod by me

## V React component

	"V React component": {
		"prefix": "VRComponent",
		"body": [
			"export const ${1:${TM_FILENAME_BASE}} = () => {",
			"	return (",
			"	  <>"
			"		  $0",
			"	  </>",
			"	)",
			"}"
			],
	"description": "Create a basic auto export const component"
	},


## V React Arrow

	"V React Arrow": {
		"prefix": "VRArrow",
		"body":[
			"const $1 = () => {",
			"	$0",
			"}"
		],
		"description": "Normal Arrow Const"
	},

# **HOOKS**

## V React Hook Custom

	"V React Hook Custom": {
		"prefix": "VRHCustom",
		"body": [
			"export const ${1:${TM_FILENAME_BASE}} = () => {",
			""
			""
			"	"
			""
			""
			"	return {",
			"		$0",
			"	}",
			"}"
			],
	"description": "Create a basic auto export const component"
	},

# V React Hook useState

	"V React Hook useState": {
		"prefix": "VRHUseState",
		"body": "const [${1}, set${1/(.*)/${1:/capitalize}/} ] = useState($0);",
		"description": "Creates a useState hook"
	},

# V React Hook useEffect

	"V React Hook useEffect": {
		"prefix": "VRHUseEffect",
		"body": [
		  "useEffect(() => {",
		  "  ${1:first}",
		  "",
		  "  return () => {",
		  "    ${2:second}",
		  "  }",
		  "}, [${3:third}])",
		  ""
		],
		"scope": "typescript,typescriptreact,javascript,javascriptreact"
	  }
