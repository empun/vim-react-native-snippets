# Vim React Native Snippets

Forked from[ Vim React Snippets ]( https://github.com/epilande/vim-react-snippets )and modified to suit my React Native development preferences.

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

Example from vim-react-snippets
![vim-react-snippets](http://i.imgur.com/ImgaW2k.gif)

## Installation

Using [vim-plug](https://github.com/junegunn/vim-plug):

```vim
" React Native code snippets
Plug 'morgsmccauley/vim-react-native-snippets'

" Ultisnips
Plug 'SirVer/ultisnips'
```

## Usage
In a JavaScript or JSX file, type a trigger name while in Insert mode, then tab.

## Snippets

#### Skeleton

| Trigger  | Content |
| -------: | ------- |
| `rrcc→`  | React Native Redux Class Component |
| `rcc→`   | React Native Class Component |
| `rfc→`   | React Native Functional Component |

#### Lifecycle

| Trigger  | Content |
| -------: | ------- |
| `cwm→`   | `componentWillMount () {...}` |
| `cdm→`   | `componentDidMount () {...}` |
| `cwrp→`  | `componentWillReceiveProps (nextProps) {...}` |
| `scup→`  | `shouldComponentUpdate (nextProps, nextState) {...}` |
| `cwup→`  | `componentWillUpdate (nextProps, nextState) {...}` |
| `cdup→`  | `componentDidUpdate (prevProps, prevState) {...}` |
| `cwu→`   | `componentWillUnmount () {...}` |
| `ren→`   | `render () {...}` |


#### PropTypes

| Trigger    | Content |
| -------:   | ------- |
| `pt→`      | `propTypes {...}` |
| `pt.a→`    | `PropTypes.array` |
| `pt.b→`    | `PropTypes.bool` |
| `pt.f→`    | `PropTypes.func` |
| `pt.n→`    | `PropTypes.number` |
| `pt.o→`    | `PropTypes.object` |
| `pt.s→`    | `PropTypes.string` |
| `pt.no→`   | `PropTypes.node` |
| `pt.e→`    | `PropTypes.element` |
| `pt.io→`   | `PropTypes.instanceOf` |
| `pt.one→`  | `PropTypes.oneOf` |
| `pt.onet→` | `PropTypes.oneOfType (Union)` |
| `pt.ao→`   | `PropTypes.arrayOf (Instances)` |
| `pt.oo→`   | `PropTypes.objectOf` |
| `pt.sh→`   | `PropTypes.shape` |
| `ir→`      | `isRequired` |

#### Others

| Trigger  | Content |
| -------: | ------- |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `set→`   | `this.setState(...)` |
| `dp→`    | `defaultProps {...}` |
| `cn→`    | `className` |
| `ref→`   | `ref` |
| `pp→`    | `${props => props}` |
