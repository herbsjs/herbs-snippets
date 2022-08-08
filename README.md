# Herbs Snippets

This extension for Visual Studio Code adds snippets for [HerbsJS](https://github.com/herbsjs).

-----------

## Usage Example
Type the keywords in snippet e.g., "step" and press enter.
Alternatively, one can also just press Ctrl+Space (Windows, Linux) or Cmd+Space (OSX) to access the available snippets in the editor.

![](docs/example.gif)

-----------

## Snippets

#### ◈ UseCases ◈

| Trigger  | Content |
| -------: | ------- |
| `uc→`   | Generate **Herbs** entire UseCase `...  usecase("My use case definition", { ...`	|
| `step→`   | Create a **Herbs** step `"Description of step": step( (ctx) => { return Ok() } )` |
| `ifstep→`   | Create a **Herbs** conditional Step  `"Description of conditional rule": ifElse( {` |
| `usec→`   | Generate instantiation of **Herbs** Usecase with all available functions |



#### ◈ Entities ◈

| Trigger  | Content |
| -------: | ------- |
| `ent→`   | Generate entire **Herbs** entity `entity('user', { prop: field(type) } )`|
| `fie→`   | Create a **Herbs** entity field `name: field(type)` |
| `fiev→`   | Create a **Herbs** entity field with validation params  `name: field(type, { validation: { presence: true } } } )` |
| `fjs→`   | Generate instantiation **Herbs** Entity `Entity.fromJSON(params)` |

----------

#### ◈ Aloe ◈
| Trigger  | Content |
| -------: | ------- |
| `spec→`   | Generate **Aloe** spec `... const spec = spec({...`	|
| `scenario→`   | Generate **Aloe** scenario `... 'Scenario name': scenario({...`	|


## Installation

1. Install Visual Studio Code
2. Launch VS Code
3. From the command palette Ctrl+Shift+P (Windows, Linux) or Cmd+Shift+P (OSX)
4. Type ext install or just simply select Install Extension or access the [marketplace link](https://marketplace.visualstudio.com/items?itemName=EndersonCosta.herbs-snippets)
5. Choose the extension - Herbs Snippets
6. Relaunch VS Code

-----------

## Releases 

### 1.0.4

- Return Ok Fix

### 1.0.3

- Update snippets

### 1.0.2

- Fix of the automatic deploy

### 1.0.1

- Fix of **Gotu** snippets
- Improve the documentation

### 1.0.0

- Initial release of Herbs Snippets

**Enjoy!**
