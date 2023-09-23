<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>Boggle.py
</h1>
<h3>◦ Unlock the Power of Words!</h3>
<h3>◦ Developed with the software and tools below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB.svg?style&logo=Python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/ReadMe-018EF5.svg?style&logo=ReadMe&logoColor=white" alt="ReadMe" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
</p>
<img src="https://img.shields.io/github/languages/top/ArieLevental/Boggle.py?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/ArieLevental/Boggle.py?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/ArieLevental/Boggle.py?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/license/ArieLevental/Boggle.py?style&color=5D6D7E" alt="GitHub license" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running Boggle.py](#-running-Boggle.py)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The project is a Python implementation of the Boggle board game, offering a fun and interactive gaming experience. It includes features like a GUI made using the tkinter library, party mode with color-changing elements, custom button and cube coloring, and sound effects. The core functionalities of the project include handling user input, updating the game board and score, validating words, generating random boards, undoing the last step, and submitting words. Overall, the project provides a comprehensive and enjoyable Boggle game experience.

---

## 📦 Features

|    | Feature            | Description                                                                                                        |
|----|--------------------|--------------------------------------------------------------------------------------------------------------------|
| ⚙️ | **Architecture**   | The codebase follows a modular architecture, with files for the Boggle game model, board randomizer, GUI, and utility functions. The BoggleController class handles game events, while the BoggleBoard class encapsulates game functionalities. Limit your response to a maximum of 200 characters.             |
| 📄 | **Documentation**  | The codebase lacks comprehensive documentation. Some files have brief explanations of their functionalities, but there is no centralized documentation for the entire project. Limit your response to a maximum of 200 characters.|
| 🔗 | **Dependencies**   | The codebase relies on the tkinter GUI library and pygame for audio. There are no major external dependencies beyond these. Limit your response to a maximum of 200 characters.|
| 🧩 | **Modularity**     | The codebase is organized into smaller components with each file serving a specific purpose, such as Boggle model, board randomizer, GUI, and utility functions. This promotes code reusability and maintainability. Limit your response to a maximum of 200 characters.|
| 🧪 | **Testing**        | It is unclear what testing strategies are implemented in the codebase, as there are no specific test files identifiable. The absence of a testing framework or dedicated test files indicates a potential testing gap. Additional testing should be considered to ensure code reliability. Limit your response to a maximum of 200 characters.       |
| ⚡️ | **Performance**    | The codebase does not raise any evident performance concerns. However, without detailed profiling or benchmarking data, it is difficult to assess the codebase's efficiency and resource usage. Limit your response to a maximum of 200 characters.|
| 🔐 | **Security**       | There is no specific mention of security measures in the codebase. If the Boggle game is intended for deployment, it should consider implementing measures such as user authentication, input validation, and secure data handling. Limit your response to a maximum of 200 characters.|
| 🔀 | **Version Control**| The codebase uses Git for version control. Each file has its commit history, allowing for version tracking and collaborative development. Efficient branching techniques like feature branching or tagging could further enhance version management. Limit your response to a maximum of 200 characters.|
| 🔌 | **Integrations**   | The codebase does not seem to have explicit integrations with other systems or services. However, it relies on the tkinter library for GUI and pygame for audio, which enables integration with the graphical and audio environments of those libraries. Limit your response to a maximum of 200 characters.|
| 📶 | **Scalability**    | The codebase does not contain explicit features or architectural decisions geared towards scalability. As it's a small-scale game, scalability might not be a significant concern. However, potential scalability considerations include extensibility for additional features or game modes. Limit your response to a maximum of 200 characters.           |

---


## 📂 Repository Structure




---

## ⚙️ Modules

<details closed><summary>Root</summary>

| File                                                                                                         | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ---                                                                                                          | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [boggle_board_randomizer.py](https://github.com/ArieLevental/Boggle.py/blob/main/boggle_board_randomizer.py) | This code is a helper file that randomizes a Boggle board. It takes a 2D list of dice configurations and returns a 2D list of randomly chosen letters from the dice configurations. The board size is fixed at 4x4.                                                                                                                                                                                                                                                                                     |
| [ex11_utils_v1.py](https://github.com/ArieLevental/Boggle.py/blob/main/ex11_utils_v1.py)                     | HTTPStatus Exception: 400                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| [boggle_model.py](https://github.com/ArieLevental/Boggle.py/blob/main/boggle_model.py)                       | The code is for a Boggle game that includes functionalities for handling user input, updating the game board and score, validating words, and generating random boards. It also includes methods for checking the validity of paths on the board, undoing the last step, and submitting words. The code uses a set of words from a file as valid words and keeps track of found words and their corresponding paths and scores. The BoggleBoard class encapsulates all the functionalities of the game. |
| [______test_ex11_utils.py](https://github.com/ArieLevental/Boggle.py/blob/main/______test_ex11_utils.py)     | Prompt exceeds max token limit: 4037.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [ex12_tests.py](https://github.com/ArieLevental/Boggle.py/blob/main/ex12_tests.py)                           | Prompt exceeds max token limit: 10078.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| [README](https://github.com/ArieLevental/Boggle.py/blob/main/README)                                         | The code is a Python implementation of the Boggle board game with additional features like party mode, custom button and cube coloring, and sound effects. It uses the tkinter GUI library and pygame for audio. The code offers a fun and interactive gaming experience.                                                                                                                                                                                                                               |
| [boggle_dict.txt](https://github.com/ArieLevental/Boggle.py/blob/main/boggle_dict.txt)                       | Prompt exceeds max token limit: 279408.                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [boggle_gui.py](https://github.com/ArieLevental/Boggle.py/blob/main/boggle_gui.py)                           | HTTPStatus Exception: 400                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| [boggle.py](https://github.com/ArieLevental/Boggle.py/blob/main/boggle.py)                                   | The code is for a Boggle game. It consists of a BoggleController class that initializes the game, creates actions for different game events such as picking a letter, undoing the last move, starting/resetting the game, and activating party mode. The code also includes methods for updating the game board, handling user input, and playing sound effects. The game is run by calling the run method of the BoggleGUI object.                                                                     |
| [ex11_utils.py](https://github.com/ArieLevental/Boggle.py/blob/main/ex11_utils.py)                           | HTTPStatus Exception: 400                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| [testing_stuff.py](https://github.com/ArieLevental/Boggle.py/blob/main/testing_stuff.py)                     | This code imports a function to randomize a boggle board, reads a text file of valid words, and generates a set of word prefixes. It also includes a timing function and a binary search function. The code measures execution time, retrieves words from the text file, creates a set of word prefixes, and performs binary searches on the prefixes.                                                                                                                                                  |

</details>

<details closed><summary>Final submition</summary>

| File                                                                                                                         | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ---                                                                                                                          | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [boggle_board_randomizer.py](https://github.com/ArieLevental/Boggle.py/blob/main/final submition/boggle_board_randomizer.py) | The code is a helper file for generating a random Boggle board. It takes a list of dice configurations and uses them to fill a 4x4 board. The function randomizes the dice indices and selects a random letter from each die to populate the board. The resulting board is returned as a 2D list of strings.                                                                                                                                                                                                                                                                                            |
| [boggle_model.py](https://github.com/ArieLevental/Boggle.py/blob/main/final submition/boggle_model.py)                       | The code consists of a Boggle game model that includes the board, valid words, found words, current word, current path, and score. It provides methods for handling user input, updating the board and score, and validating words. The model uses a file to generate a set of valid words and implements functions to generate possible moves, check if a path is valid, undo the last step, clear the current word, reset the board, update found words, submit a word, and retrieve game information such as found words, score, characters list, board coordinates, current path, and current word. |
| [README](https://github.com/ArieLevental/Boggle.py/blob/main/final submition/README)                                         | The Boggle game is a Python program with a GUI made using the tkinter library. It includes features like a party mode with color-changing elements and sound effects. The game also has custom coloring for the board and smart coloring for selected cube paths. The code allows for contributions and was created by Adir Barak and Arie Levental.                                                                                                                                                                                                                                                    |
| [boggle_dict.txt](https://github.com/ArieLevental/Boggle.py/blob/main/final submition/boggle_dict.txt)                       | Prompt exceeds max token limit: 279408.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [boggle_gui.py](https://github.com/ArieLevental/Boggle.py/blob/main/final submition/boggle_gui.py)                           | HTTPStatus Exception: 400                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| [boggle.py](https://github.com/ArieLevental/Boggle.py/blob/main/final submition/boggle.py)                                   | The code is for a Boggle game program. It creates a GUI and a game model, and implements various actions like picking a letter, undoing the last move, starting/resetting the game, and activating party mode. Sound effects are played for different actions. The program also handles cube interactions and updates the display accordingly. It provides a comprehensive Boggle game experience.                                                                                                                                                                                                      |
| [ex11_utils.py](https://github.com/ArieLevental/Boggle.py/blob/main/final submition/ex11_utils.py)                           | HTTPStatus Exception: 400                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |

</details>

<details closed><summary>Ex11 - additional files</summary>

| File                                                                                                                                 | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                                                                  | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [boggle_board_randomizer.py](https://github.com/ArieLevental/Boggle.py/blob/main/Ex11 - Additional Files/boggle_board_randomizer.py) | This code generates a random Boggle board by randomly picking letters from a given list of dice faces. It shuffles the dice positions and iterates through the board to select a random letter from each die. The resulting board is a 4x4 grid of letters.                                                                                                                                                                                                                                                  |
| [README](https://github.com/ArieLevental/Boggle.py/blob/main/Ex11 - Additional Files/README)                                         | The code performs a variety of functions, including data manipulation, input validation, and output generation. It has modules for database connectivity, API integration, and user authentication. Additionally, it incorporates error handling mechanisms and implements a logging system for monitoring and debugging purposes. It also supports multi-threading and scalability for efficient processing of large datasets.                                                                              |
| [boggle_dict.txt](https://github.com/ArieLevental/Boggle.py/blob/main/Ex11 - Additional Files/boggle_dict.txt)                       | Prompt exceeds max token limit: 279408.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [ex11_utils.py](https://github.com/ArieLevental/Boggle.py/blob/main/Ex11 - Additional Files/ex11_utils.py)                           | The code defines several functions related to a word puzzle board and finding paths on it. The `is_valid_path` function checks if a given path spells any of the given words. The `find_length_n_paths` function finds all paths of length n on the board that spell any of the given words. The `find_length_n_words` function finds all paths on the board that spell words of length n. The `max_score_paths` function finds all paths on the board that maximize the score based on a scoring mechanism. |

</details>

---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ Dependency 1`

`- ℹ️ Dependency 2`

`- ℹ️ ...`

### 🔧 Installation

1. Clone the Boggle.py repository:
```sh
git clone https://github.com/ArieLevental/Boggle.py
```

2. Change to the project directory:
```sh
cd Boggle.py
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🤖 Running Boggle.py

```sh
python main.py
```

### 🧪 Tests
```sh
pytest
```

---


## 🛣 Roadmap

> - [X] `ℹ️  Task 1: Implement X`
> - [ ] `ℹ️  Task 2: Implement Y`
> - [ ] `ℹ️ ...`


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  LICENSE-TYPE` License. See the [LICENSE-Type](LICENSE) file for additional info.

---

## 👏 Acknowledgments

`- ℹ️ List any resources, contributors, inspiration, etc.`

---


# BOGGLE

This is a variation of the Boggle board-game, made with python and the tkinter GUI library. There are also some custom features and smart algorithms involved.

## RUN

Use this command from terminal
```bash
python3 boggle.py
```

## GAME WIKI & RULES
[Wikipedia - Boggle](https://en.wikipedia.org/wiki/Boggle)

## SPECIAL FEATURES

We added a special party mode to the game, so you can enjoy it double-time!
Some of the features are a custom button, changing colors, and sound effects.

```python
    def party_mode_activated(self):


self.party_mode = 1
# self.play_sound("media/cute_song.mp3")
for cube in self.cubes:
    if cube.marked:
        continue
    cube["bg"] = self.random_color()

for button in self.buttons.values():
    button["bg"] = self.random_color()
self._timer["bg"] = self.random_color()
self._score["bg"] = self.random_color()
self._found_words["bg"] = self.random_color()
self.buttons["PARTY"]["image"] = self.meme
self._display_label["bg"] = self.random_color()


def random_color(self):
    hex_color = ["#" + ''.join([random.choice('ABCDEF0123456789') for _ in range(6)])]
    return hex_color


def party_action(self):
    self.play_sound("media/wow.mp3")
    self._gui.party_mode_activated()

```

Added sound to all buttons, using pygame library:
```python
    def play_sound(self, soundtrack: str):
        pygame.mixer.music.load(soundtrack)
        pygame.mixer.music.play()
```
![alt text](https://i.gyazo.com/6982b45ca1c84e2a86b83c5981999440.png)

Custom coloring of default board and smart coloring of picked cube path:

```python
    def hue_red_color(self, multipler):
    rgb = 255, max(208 - 13 * multipler, 0), max(208 - 13 * multipler, 0)
    rgb_to_hex = "#" + '%02x%02x%02x' % rgb
    return rgb_to_hex


def _make_cube(self, cube_chars: str, row: int, col: int, rowspan: int = 1, columnspan: int = 1) -> tki.Button:
    cube = tki.Button(self._lower_frame, text=cube_chars, **BUTTON_STYLE)
    cube.marked = False
    if row % 2 == col % 2:
        cube["bg"] = REGULAR_COLOR_2
    cube.grid(row=row, column=col, rowspan=rowspan, columnspan=columnspan, sticky=tki.NSEW)
    self.cubes.append(cube)
```

## CONTRIBUTING

Project made by Adir Barak and Arie Levental ©

Enjoy the game.
