# ReactSnippets
My Custom Snippets for react

VRComponent :
```
export const $1 = () => {
  return (
    <>
      $0
    </>
  )
}
```

VRUseState :
```
const [${1}, set${1/(.*)/${1:/capitalize}/} ] = useState($0);
```

VRArrow :
```
const $1 = () => {
  $0
}
```
