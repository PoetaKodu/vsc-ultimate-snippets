# VSC Ultimate C++ Snippets

An ultimate collection of C++ snippets for [VS Code](https://code.visualstudio.com).

[**Installation**](#-installation) | [**Snippet list**](#snippet-list) | [**Contributing**](#-contributing) | [**Presentation**](#-presentation) 
## 😄 Overview

![Snippet - Vector](img/snip_vec.gif)


... and many, many more.

## ⬇ Installation

1. Install [this VS Code extension](https://marketplace.visualstudio.com/items?itemName=draivin.hsnips)
2. Put [cpp.hsnips](cpp.hsnips) file into one of the following folders:
   - Windows: `%APPDATA%\Code\User\hsnips\`
   - Linux: `$HOME/.config/Code/User/hsnips/`
   - Mac: `$HOME/Library/Application Support/Code/User/hsnips/`

Done, optionally run action **Reload snippets**, or reopen editor.

## Snippet list:
- `@vec` -> `std::vector`
- **TODO**: more helper snippets
- `@fif` -> `std::find_if` (lambda)
- `@ffif` -> `std::find_if` (function)
- `@find` -> `std::find` (value)
- `@anyof` -> `std::any_of` (lambda)
- `@fanyof` -> `std::any_of` (function)
- `@allof` -> `std::all_of` (lambda)
- `@fallof` -> `std::all_of` (function)
- `@noneof` -> `std::none_of` (lambda)
- `@fnoneof` -> `std::none_of` (function)
- `@each` -> `std::for_each` (lambda)
- `@feach` -> `std::for_each` (function)
- `@neach` -> `std::for_each_n` (lambda)
- `@fneach` -> `std::for_each_n` (function)
- `@cif` -> `std::count_if` (lambda)
- `@fcif` -> `std::count_if` (function)
- `@count` -> `std::count` (value)
- `@=>` -> Lambda returning element
- **TODO**: entire algorithm library

## ⛑ Contributing

Feel free to put pull request, modifying [cpp.hsnips](cpp.hsnips)
We all will benefit from this.

## 🖼 Presentation:


### Vector definition

```cpp
varName@vec
```

![Snippet - Vector](img/snip_vec.gif)


### Standard `<algorithm>`


#### `std::find_if` (lambda)

```cpp
someRange@fif
```

![Snippet - find if](img/snip_fif.gif)

#### `std::find_if` (function)

```cpp
someRange@ffif
```

![Snippet - find if](img/snip_ffif.gif)


