# Awesome Command Line (CLI/TUI) Programs with stars

This repository - to the best of my knowledge - contains the largest collection of command line (CLI/TUI) tools available in the form of awesome list.
With source information maintained in a handy CSV file.

To contribute, see the [indications](CONTRIBUTING.md).
Read the instructions before rushing at changing the README file: you must edit the CSV files, not the README!

Some links are available to [related resources](#resources).

Summary:

* Apps/tools: **2207**
* Categories: **87**

# Contents

## [Core Utils](#core-utils-1)

* [File listing (alternatives to ls)](#ls) (11)
* [Directory changers (alternatives to cd)](#cd) (21)
* [File finding (alternatives to find)](#find) (9)
* [File deletion and trash bin (alternatives to rm)](#rm) (14)
* [History management](#history) (6)
* [Diff](#diff) (12)
* [Text search (alternatives to grep)](#text-search) (16)
* [Text search and replace (alternatives to sed)](#text-search-replace) (8)
* [Disk usage analyzers](#disk-analyzer) (13)
* [Process viewers and monitoring (alternatives to top)](#monitor-top) (28)
* [Clean up of files and directories](#file-dir-cleanup) (17)

## [File and Filesystem Management](#file-and-filesystem-management-1)

* [File managers](#file-manager) (27)
* [File explorer and tree visualization](#file-explorer) (11)
* [File and file system handling](#file-handling) (30)
* [Backup](#backup) (20)
* [File watching for changes](#file-watch) (8)
* [File renamers](#file-renamer) (15)
* [File systems](#file-system) (4)
* [File format converters](#conversion) (17)

## [Text and Data Processing](#text-and-data-processing-1)

* [Text processing](#text-processing) (58)
* [Data management](#data-management) (18)
* [Data management - JSON/YAML/etc.](#data-management-json) (47)
* [Data management - Tabular data](#data-management-tabular) (36)
* [Fuzzy finders and option pickers](#option-picker) (18)
* [Markdown](#markdown) (9)

## [Development and Programming](#development-and-programming-1)

* [Editors](#editors) (32)
* [Git and accessories](#git) (80)
* [Versioning](#versioning) (9)
* [Programming](#programming) (75)
* [Program templates and boilerplate](#programming-boilerplate) (13)
* [DevOps](#devops) (22)
* [Web development](#webdev) (37)
* [Co-pilot](#copilot) (12)

## [System and Terminal](#system-and-terminal-1)

* [System tools](#system) (45)
* [Terminals](#terminal) (14)
* [Terminal multiplexers and accessories](#terminal-mux) (13)
* [Shells](#shells) (26)
* [Prompts](#prompt) (14)
* [Copy/paste and clipboard](#copy-paste) (11)
* [System monitoring](#monitor) (54)

## [Environment Management Tools](#environment-management-tools-1)

* [Package managers](#package-manager) (25)
* [Containerization and virtualization](#vm) (25)
* [Command launchers](#launcher) (28)
* [Dotfile managers](#dotfiles) (5)
* [Font management](#font) (5)

## [Communication and Networking](#communication-and-networking-1)

* [Email](#email) (23)
* [Chat and instant messaging](#chat) (51)
* [Networking](#networking) (87)
* [Connection managers](#connection-manager) (12)
* [Data transfer](#transfer) (47)
* [Torrent](#torrent) (10)
* [RSS](#rss) (12)
* [Web browser](#browser) (19)
* [Online search and resources](#online) (39)

## [Personal Information Management](#personal-information-management-1)

* [Todo managers](#todo-manager) (43)
* [Time trackers](#time-tracker) (29)
* [Note taking](#note-taking) (34)
* [Organizers and calendars](#organizers) (22)
* [Financial tools](#financial) (25)

## [Productivity](#productivity-1)

* [AI / LLM integration](#ai) (48)
* [Productivity](#productivity) (19)
* [Office tools](#office) (23)
* [Writing](#writing) (12)
* [Calculators](#calc) (21)
* [Pastebin](#pastebin) (2)
* [Commands cheatsheet and snippets](#cheatsheet) (33)
* [AI terminal command generator](#ai-cli-commands) (16)

## [Media and Creative](#media-and-creative-1)

* [Graphics](#graphics) (53)
* [Video](#video) (15)
* [Sound and music](#music) (53)
* [Music players](#audio-player) (20)
* [Animation](#animation) (44)
* [Viewers](#viewers) (49)
* [Screen savers](#screensaver) (7)
* [Screen recorder](#screen-recorder) (12)

## [Security and Package Management](#security-and-package-management-1)

* [Ciphering and steganography](#crypto) (17)
* [Security](#security) (25)
* [Password managers](#password-manager) (25)

## [Utilities and Miscellaneous](#utilities-and-miscellaneous-1)

* [Utilities](#utility) (46)
* [Weather](#weather) (6)

## [Learning and Leisure](#learning-and-leisure-1)

* [Learning and didactic tools](#learning) (9)
* [Anki, decks and flashcards](#flashcard) (10)
* [Typing test and practice](#typing) (21)
* [Games](#games) (100)
* [Funny tools](#funny) (23)
* [Religion](#religion) (6)
* [Science](#science) (21)

# <a name="Core-Utils"></a>Core Utils

## <a name="ls"></a>File listing (alternatives to ls)

List directory content and files, with colors or icons; alternatives to `ls`.

* [eza](https://github.com/eza-community/eza) ⭐ 23,025 | 🐛 437 | 🌐 Rust | 📅 2026-08-06 - eza is a modern, *maintained* replacement for `ls`, built on `exa`.
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,191 | 🐛 206 | 🌐 Rust | 📅 2026-08-17 - This project is a rewrite of GNU ls with lots of added features like colors, icons, tree-view, more formatting options etc. The project is heavily inspired by the super colorls project.
* [colorls](https://github.com/athityakumar/colorls) ⭐ 5,134 | 🐛 87 | 🌐 Ruby | 📅 2026-07-27 - A Ruby script that colorizes the `ls` output with color and icons.
* [vivid](https://github.com/sharkdp/vivid) ⭐ 2,257 | 🐛 30 | 🌐 Rust | 📅 2026-08-24 - A themeable LS\_COLORS generator with a rich filetype datebase.
* [nat](https://github.com/willdoescode/nat) ⭐ 1,262 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - Complete replacement for the `ls` command.
* [stree](https://github.com/orangekame3/stree) ⭐ 144 | 🐛 0 | 🌐 Go | 📅 2024-07-17 - A CLI tool designed to visualize the directory tree structure of an S3 bucket.
* [ll](https://github.com/antonmedv/ll) ⭐ 53 | 🐛 0 | 📅 2025-12-05 - ls with git status.
* [lscoltui](https://github.com/breynard0/lscoltui) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2025-07-08 - A TUI tool for changing the colours of ls.
* [lsnotes](https://github.com/aeilot/lsnotes) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2025-08-09 - The program lets you add a description to your directories.
* [pretty-ls](https://github.com/ix/pretty-ls) ⭐ 12 | 🐛 2 | 🌐 Rust | 📅 2017-01-07 - Rust ls clone with pretty colors.
* [Files-Sort-py](https://github.com/AfzGit/Files-Sort-py) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-05-21 - Python-based file sorter that sorts file by extensions, size, and time.

## <a name="cd"></a>Directory changers (alternatives to cd)

Programs for improving the efficiency of directory traversal by remembering common paths and other approaches; alternatives to the `cd` command.

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 38,818 | 🐛 136 | 🌐 Rust | 📅 2026-08-24 - It remembers which directories you use most frequently, so you can "jump" to them in just a few keystrokes.
* [z](https://github.com/rupa/z) ⭐ 17,043 | 🐛 107 | 🌐 Shell | 📅 2024-06-19 - Directory changer based on aging and 'frecency'.
* [autojump](https://github.com/wting/autojump) ⭐ 16,961 | 🐛 231 | 🌐 Python | 📅 2025-02-27 - A cd command that maintains a database of most visited paths and allows the access to a directory with shortened versions of the path.
* [z.lua](https://github.com/skywind3000/z.lua) ⭐ 3,144 | 🐛 73 | 🌐 Lua | 📅 2026-08-10 - Directory changer that learns your habits.
* [enhancd](https://github.com/babarot/enhancd) ⭐ 2,711 | 🐛 17 | 🌐 Shell | 📅 2025-01-24 - A next-generation cd command with your interactive filter.
* [fz](https://github.com/changyuheng/fz.sh) ⭐ 574 | 🐛 9 | 🌐 Shell | 📅 2024-02-25 - Fuzzy tab completion for z.
* [Shunpo](https://github.com/egurapha/Shunpo) ⭐ 444 | 🐛 1 | 🌐 Shell | 📅 2026-08-03 - A minimalist bash tool that makes directory navigation just a little bit faster.
* [pm](https://github.com/Angelmmiguel/pm) ⭐ 205 | 🐛 8 | 🌐 Shell | 📅 2021-04-14 - The easy way to switch between your projects on ZSH. In short, another directory changer.
* [pazi](https://github.com/euank/pazi) ⭐ 167 | 🐛 33 | 🌐 Rust | 📅 2026-08-09 - Fast autojump helper.
* [nav](https://github.com/dkaslovsky/nav) ⭐ 131 | 🐛 0 | 🌐 Go | 📅 2026-03-15 - Terminal navigator for interactive ls workflows.
* [cdwe](https://github.com/synoet/cdwe) ⭐ 45 | 🐛 2 | 🌐 Rust | 📅 2024-06-15 - (cd with env vars) Wrapper of the cd command that sets and unsets env vars when you change dir based on a config file.
* [navita](https://github.com/CodesOfRishi/navita) ⭐ 44 | 🐛 1 | 🌐 Shell | 📅 2026-07-16 - A command-line tool for fast directory navigation in Bash & Zsh, ranking directories by frequency and recency. It enables quick fuzzy searches, recent history access, and smooth directory switching for efficient terminal workflows.
* [slingshot](https://github.com/caio-ishikawa/slingshot) ⭐ 36 | 🐛 0 | 🌐 Rust | 📅 2023-09-20 - Lightweight command line tool to quickly navigate across folders.
* [Jmp](https://github.com/gholmes829/Jmp) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2023-03-28 - Change directory with smart searching of the path specified through regex.
* [fastdiract](https://github.com/dp12/fastdiract) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2026-08-19 - Lightning-fast cd and command execution.
* [ff](https://github.com/akymos/ff) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2023-12-07 - ff is a command-line tool to manage favorite folders, creating an alias, to be used via shell directly with the cd command.
* [Apparition](https://github.com/david-haerer/apparition) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2023-11-08 - Apparition allows giving names to paths, so that moving to the specific path can be done by using the name; it also allows managing the list of assigned names.
* [qcd](https://github.com/ClaasBontus/qcd_rs) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2023-09-05 - A tool to change to another directory by just by entering commands like `qcd 3` and step back to where you came from with `qcd -o`. Frequently visited directories are stored in a sqlite3 database.
* [zm](https://github.com/benrutter/zm) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2024-02-16 - Improved cd.
* [menucd](https://github.com/andy5995/menucd) ⭐ 3 | 🐛 1 | 🌐 C | 📅 2026-06-20 - Directory browser and changer for the command line.
* [broot](https://dystroy.org/broot/) - broot displays an optimized (omitting unnecessary content) tree view of the filesystem, allowing to fuzzy search files and folder, and move to specified directories.

## <a name="find"></a>File finding (alternatives to find)

Search the filesystem looking for files with specific characteristics, e.g., names; alternatives to `find`.

* [fd](https://github.com/sharkdp/fd) ⭐ 44,190 | 🐛 189 | 🌐 Rust | 📅 2026-08-11 - A simple, fast, and user-friendly alternative to find. Written in Rust.
* [bfs](https://github.com/tavianator/bfs) ⭐ 1,258 | 🐛 12 | 🌐 C | 📅 2026-08-24 - A breadth-first version of the UNIX find command.
* [happyfinder](https://github.com/hugows/hf) ⭐ 335 | 🐛 4 | 🌐 Go | 📅 2024-11-11 - (another) Fuzzy file finder for the command line.
* [friendly-find](https://github.com/sjl/friendly-find) ⭐ 223 | 🐛 1 | 🌐 Python | 📅 2022-08-25 - Usable replacement for find.
* [rawhide](https://github.com/raforg/rawhide) ⭐ 59 | 🐛 0 | 🌐 C | 📅 2025-12-18 - File finder that uses C expressions to specify the filenames.
* [Findpick](https://github.com/thingsiplay/findpick) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2024-02-20 - General purpose file picker combining "find" command with a fuzzy finder.
* [trovatore](https://github.com/trikko/trovatore) ⭐ 8 | 🐛 0 | 🌐 D | 📅 2025-04-17 - A fast command-line tool for searching files by name.
* [crtag](https://github.com/CarrotyLemons/crtag) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-07-02 - CLI for searching directories by tag (UNIX and OS).
* [plocate](https://plocate.sesse.net/) - A much faster locate; plocate is a locate based on posting lists, completely replacing mlocate with a much faster (and smaller) index.

## <a name="rm"></a>File deletion and trash bin (alternatives to rm)

Tools to manage the deletion of files/directories, often with the support of a trash can, i.e., the ability to restore deleted items.

* [RecoverPy](https://github.com/PabloLec/RecoverPy) ⭐ 1,785 | 🐛 4 | 🌐 Python | 📅 2026-08-03 - Recover deleted files and overwritten data. It scans every block of the partition. You can even find a string in binary files.
* [rip](https://github.com/nivekuil/rip) ⭐ 1,729 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - Move and restore items from the graveyard (by default, `/tmp/graveyard-$USER` if $XDG\_DATA\_HOME is not set and `$XDG_DATA_HOME/graveyard` otherwise)
* [trash-cli](https://github.com/sindresorhus/trash-cli) ⭐ 1,412 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-02 - Move files and folders to the trash on Linux (XDG trash), macOS (`macOS-trash` library) and Windows (`recycle-bin` library).
* [gomi](https://github.com/babarot/gomi) ⭐ 565 | 🐛 2 | 🌐 Go | 📅 2026-06-07 - UNIX rm command with a safety net.
* [gtrash](https://github.com/umlx5h/gtrash) ⭐ 319 | 🐛 13 | 🌐 Go | 📅 2025-05-22 - TUI for moving and restoring items from the XDG trash. Fully compliant with the FreeDesktop.org specification.
* [undelete-btrfs](https://github.com/danthem/undelete-btrfs) ⭐ 292 | 🐛 3 | 🌐 Shell | 📅 2026-08-18 - Automate the generation of path regex for BTRFS restore and attempt the restore for you in 3 levels. The longer a file has existed prior to being deleted, the more likely it is to be recovered.
* [rm-trash](https://github.com/nateshmbhat/rm-trash) ⭐ 51 | 🐛 2 | 🌐 Shell | 📅 2018-11-20 - Meant to be used in place of `rm` in Linux, supporting all its arguments. It can move and restore the files from the XDG trash.
* [trasher](https://github.com/clementnerma/trasher) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2025-04-18 - Delete files to a trash directory instead of deleting them immediately. Uses its own trash instead of the XDG one.
* [Brash](https://github.com/zakariagatter/brash) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2023-03-29 - Move and restore items from the XDG trash. Written in pure Bash.
* [trashbhuwan](https://github.com/tribhuwan-kumar/trashbhuwan) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2025-07-28 - Trashing CLI application for Linux distros, written in C.
* [del](https://fex.belwue.de/fstools/del.html) - Save deleted files to a .del/ subdirectory in the same directory.
* [extundelete](https://extundelete.sourceforge.net/) - Recover deleted files from an ext3 or ext4 partition through its journal.
* [rmw](https://remove-to-waste.info/) - (ReMove to Waste) is a trashcan/recycle bin utility for the command line. It can move and restore files to and from directories specified in a configuration file.
* [testdisk](https://www.cgsecurity.org/wiki/TestDisk) - Lets you undelete files from FAT, exFAT, NTFS, and ext2 filesystems and do many other things, e.g., fix partition tables and recover deleted partitions.

## <a name="history"></a>History management

Programs to replace or improve the management of command line history.

* [mcfly](https://github.com/cantino/mcfly) ⭐ 7,781 | 🐛 135 | 🌐 Rust | 📅 2026-04-14 - Intelligent context-aware search engine for your shell history with TUI.
* [hstr](https://github.com/dvorka/hstr) ⭐ 4,453 | 🐛 185 | 🌐 C | 📅 2026-05-29 - Manage the shell history. It has a powerful visual search and execution of previous commands, and history editing capabilities.
* [hiSHtory](https://github.com/ddworken/hishtory) ⭐ 3,112 | 🐛 63 | 🌐 Go | 📅 2026-03-18 - A better shell history that stores context (directory, succeeded or failed, how long it took, etc). The history is stored locally and end-to-end encrypted for syncing to other computers.
* [his](https://github.com/terroo/his) ⭐ 68 | 🐛 2 | 🌐 C++ | 📅 2025-07-24 - A command history utility with icons and colors that works on Windows and GNU/Linux.
* [Bevel](https://github.com/NorfairKing/bevel) ⭐ 43 | 🐛 7 | 🌐 Haskell | 📅 2026-06-03 - Command line history in an SQLite database for effective reuse.
* [atuin](https://github.com/ellie/atuin) ⭐ 23 | 🐛 0 | 📅 2026-02-10 - Atuin replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronization of your history between machines, via an Atuin server.

## <a name="diff"></a>Diff

Calculation of diffs between files and data, even with context or semantic awareness (i.e., considering the meaning of the data).

* [delta](https://github.com/dandavison/delta) ⭐ 31,852 | 🐛 430 | 🌐 Rust | 📅 2026-08-02 - A syntax-highlighter for git and diff output.
* [Difftastic](https://github.com/Wilfred/difftastic) ⭐ 25,816 | 🐛 298 | 🌐 Rust | 📅 2026-08-23 - Syntax-aware structured diff tool.
* [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) ⭐ 18,082 | 🐛 4 | 🌐 Perl | 📅 2026-08-19 - Make your diffs human-readable instead of machine-readable.
* [dyff](https://github.com/homeport/dyff) ⭐ 1,876 | 🐛 69 | 🌐 Go | 📅 2026-08-17 - A diff tool for YAML files, and sometimes JSON.
* [ydiff](https://github.com/ymattw/ydiff) ⭐ 931 | 🐛 1 | 🌐 Python | 📅 2026-05-20 - View colored, incremental diff.
* [pdf-diff](https://github.com/serhack/pdf-diff) ⭐ 868 | 🐛 5 | 🌐 Go | 📅 2023-05-08 - A tool for visualizing differences between two PDF files. Mainly dedicated to editors that usually spends a lot of hours on several PDFs.
* [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) ⭐ 602 | 🐛 16 | 🌐 TypeScript | 📅 2026-02-06 - Parse git diffs as JSON and generate pretty HTML.
* [csv-diff](https://github.com/simonw/csv-diff) ⭐ 339 | 🐛 38 | 🌐 Python | 📅 2024-09-06 - Python CLI tool and library for diffing CSV and JSON files
* [Dirdiff](https://github.com/OCamlPro/dirdiff) ⭐ 93 | 🐛 3 | 🌐 Rust | 📅 2022-11-29 - Efficiently compute the differences between two directories.
* [leven-cli](https://github.com/sindresorhus/leven-cli) ⭐ 48 | 🐛 0 | 🌐 JavaScript | 📅 2021-08-10 - Measure the difference between two strings using the Levenshtein distance algorithm.
* [sesdiff](https://github.com/proycon/sesdiff) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2024-10-15 - Generates a shortest edit script (Myers' diff algorithm) to indicate how to get from the strings in column A to the strings in column B. Also provides the edit distance (levenshtein).
* [LLM Prompt Semantic Diff](https://github.com/aatakansalar/llm-prompt-semantic-diff) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-07-01 - A CLI tool for managing and comparing LLM prompts using semantic diffing instead of traditional text-based comparison.

## <a name="text-search"></a>Text search (alternatives to grep)

Search files and exploring directory trees to look for text or patterns (RegEx) contained in files; alternatives to the `grep` command.

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 67,568 | 🐛 182 | 🌐 Rust | 📅 2026-08-04 - Recursively searches directories for a regex pattern.
* [ag](https://github.com/ggreer/the_silver_searcher) ⭐ 27,106 | 🐛 564 | 🌐 C | 📅 2024-06-16 - (The silver searcher) - a text search utility targeted to source code; it skips versioning systems data directories; it is inspired by `ack`, but faster.
* [ast-grep](https://github.com/ast-grep/ast-grep) ⭐ 15,634 | 🐛 45 | 🌐 Rust | 📅 2026-08-24 - A CLI tool for code structural search, lint and rewriting.
* [ripgrep-all](https://github.com/phiresky/ripgrep-all) ⭐ 9,824 | 🐛 73 | 🌐 Rust | 📅 2026-03-25 - grep in text files but also search in PDFs, E-Books, office documents, zip, tar.gz, etc.
* [ugrep](https://github.com/Genivia/ugrep) ⭐ 3,251 | 🐛 7 | 🌐 C++ | 📅 2026-08-24 - Ultra fast grep with interactive TUI, fuzzy search, boolean queries, hexdumps and more.
* [semantic-grep](https://github.com/arunsupe/semantic-grep) ⭐ 1,246 | 🐛 0 | 🌐 Go | 📅 2024-08-19 - grep for words with similar meaning to the query.
* [vgrep](https://github.com/vrothberg/vgrep) ⭐ 704 | 🐛 2 | 🌐 Go | 📅 2026-08-21 - User-friendly pager for grep.
* [krep](https://github.com/davidesantangelo/krep) ⭐ 454 | 🐛 7 | 🌐 C | 📅 2026-07-01 - Blazingly fast text search tool with multiple algorithms (Boyer-Moore, KMP, Rabin-Karp), SIMD acceleration, multi-threading, and regex support. Outperforms traditional tools with memory-mapped I/O and hardware optimizations for who need rapid pattern matching at scale.
* [zfind](https://github.com/laktak/zfind) ⭐ 409 | 🐛 1 | 🌐 Go | 📅 2025-09-03 - Search for files (even inside tar/zip/7z/rar) using a SQL-WHERE filter.
* [hypergrep](https://github.com/p-ranav/hypergrep) ⭐ 246 | 🐛 3 | 🌐 C++ | 📅 2023-06-09 - Recursively search directories for a regex pattern using Intel Hypescan.
* [Csope](https://github.com/agvxov/csope) ⭐ 70 | 🐛 0 | 🌐 C | 📅 2026-08-04 - C source code browser - Fork of Cscope version 15,9, with various improvements.
* [hae](https://github.com/eeroel/hae) ⭐ 50 | 🐛 6 | 🌐 C++ | 📅 2024-01-20 - Like grep but with natural language queries; useful to retrieve paragraphs of text that deal with specific topics.
* [nocjk](https://github.com/aethiopicuschan/nocjk) ⭐ 0 | 🐛 1 | 🌐 Go | 📅 2026-02-08 - A simple CLI tool and library to detect CJK (Chinese, Japanese, and Korean) text.
* [ack](http://beyondgrep.com/) - A tool like `grep` optimized for programmers; written in Perl, it speeds up searches thanks to skipping non-interesting directories, such as `.git`.
* [paragrep](http://software.clapper.org/paragrep/) - Greps regular expressions in a text file(s) and prints out the paragraphs containing those expressions, a paragraph is defined as a block of text delimited by an empty or blank line, fully customizable via command line parameters.
* [sift](https://sift-tool.org/) - Fast and powerful alternative to `grep`; it targets flexibility and performance: can be as fast as `grep` and allows specifying complex expressions to find text.

## <a name="text-search-replace"></a>Text search and replace (alternatives to sed)

Tools to search text within files and perform operations on it, such as text replacement; alternatives to `sed`.

* [sd](https://github.com/chmln/sd) ⭐ 7,321 | 🐛 77 | 🌐 Rust | 📅 2026-02-25 - s\[earch] & d\[isplace] - An intuitive find & replace CLI a possible replacement for sed.
* [scooter](https://github.com/thomasschafer/scooter) ⭐ 1,290 | 🐛 19 | 🌐 Rust | 📅 2026-08-22 - Interactive find-and-replace TUI app; By default the program recursively searches through files in the current directory and can also be used to process text from stdin.
* [amber](https://github.com/dalance/amber) ⭐ 953 | 🐛 20 | 🌐 Rust | 📅 2026-08-07 - Code search / replace tool.
* [srgn](https://github.com/alexpovel/srgn) ⭐ 909 | 🐛 4 | 🌐 Rust | 📅 2026-08-04 - A code surgeon for precise text and code transplantation. A marriage of `tr`/`sed`, `rg` and `tree-sitter`.
* [teip](https://github.com/greymd/teip) ⭐ 598 | 🐛 9 | 🌐 Rust | 📅 2026-04-22 - Select partial standard input and replace with the result of another command.
* [repgrep](https://github.com/acheronfail/repgrep) ⭐ 524 | 🐛 12 | 🌐 Rust | 📅 2025-06-18 - A replacer that uses ripgrep for finding and provides an interactive interface to replace the text.
* [Rep](https://github.com/robenkleene/rep-grep) ⭐ 108 | 🐛 1 | 🌐 Rust | 📅 2026-02-22 - Rep is a command-line utility that takes grep-formatted lines via standard input, and performs a find-and-replace on them.
* [frep](https://github.com/thomasschafer/frep) ⚠️ Archived - Fast find-and-replace tool; search and replace in files in directories or process stdin.

## <a name="disk-analyzer"></a>Disk usage analyzers

Programs to analyze and summarize the usage of disks, visualize and report the size of directories and sub-directories, etc..

* [duf](https://github.com/muesli/duf) ⭐ 15,272 | 🐛 82 | 🌐 Go | 📅 2026-01-13 - Disk Usage/Free Utility.
* [Dust](https://github.com/bootandy/dust) ⭐ 12,178 | 🐛 8 | 🌐 Rust | 📅 2026-08-19 - du + rust = dust. Like du but more intuitive.
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,171 | 🐛 32 | 🌐 Rust | 📅 2026-08-24 - Disk Usage Analyzer. Learn about the usage of disk space of a given directory with parallel access to max out SSD exploration.
* [gdu](https://github.com/dundee/gdu) ⭐ 5,927 | 🐛 56 | 🌐 Go | 📅 2026-08-24 - Pretty fast disk usage analyzer written in Go. Gdu is intended primarily for SSD disks where it can fully utilize parallel processing. However, HDDs work as well, but the performance gain is not so huge.
* [diskonaut](https://github.com/imsnif/diskonaut) ⭐ 3,117 | 🐛 45 | 🌐 Rust | 📅 2024-03-07 - Terminal disk space navigator that traverse the file-system with a TUI interface.
* [erdtree](https://github.com/solidiquis/erdtree) ⭐ 2,594 | 🐛 36 | 🌐 Rust | 📅 2024-05-19 - A multithreaded file-tree visualizer and disk usage analyzer.
* [diskus](https://github.com/sharkdp/diskus) ⭐ 1,236 | 🐛 13 | 🌐 Rust | 📅 2026-02-14 - Minimal, fast alternative to du -sh.
* [dutree](https://github.com/nachoparker/dutree) ⭐ 876 | 🐛 22 | 🌐 Rust | 📅 2022-06-29 - A tool to analyze file system usage written in Rust.
* [vizex](https://github.com/bexxmodd/vizex) ⭐ 248 | 🐛 5 | 🌐 Python | 📅 2022-04-20 - Visualize the disk space usage for every partition and media on the user's machine.
* [dfc](https://github.com/rolinh/dfc) ⭐ 116 | 🐛 14 | 🌐 C | 📅 2025-10-14 - Report file system space usage information with style.
* [cdu](http://arsunik.free.fr/prog/cdu.html) - (colored `du`) - a Perl script that calls `du` and displays a pretty histogram with optional colors allowing to immediately see the directories which take most disk space.
* [mac-storage-manager](https://github.com/NarekMosisian/mac-storage-manager) - A cross‑platform CLI for macOS & Linux that reclaims disk space by identifying and removing large apps and associated files, with multi‑language interface (40+ translations), robust logging, and seamless Homebrew integration (macOS) for a safe, interactive cleanup experience.
* [ncdu](https://dev.yorhel.nl/ncdu) - "A disk usage analyzer with a ncurses interface. It is designed to find space hogs on a remote server where you don't have an entire graphical setup available."

## <a name="monitor-top"></a>Process viewers and monitoring (alternatives to top)

Programs to list and monitor currently running processes; alternatives to the `top` command.

* [Btop++](https://github.com/aristocratos/btop) ⭐ 34,196 | 🐛 528 | 🌐 C++ | 📅 2026-08-23 - Resource monitor that shows usage and stats for processor, memory, disks, network, and processes. C++ version and continuation of [bashtop](https://github.com/aristocratos/bashtop) ⭐ 11,118 | 🐛 64 | 🌐 Shell | 📅 2023-08-21 and [bpytop](https://github.com/aristocratos/bpytop) ⭐ 10,920 | 🐛 99 | 🌐 Python | 📅 2025-06-01.
* [bottom](https://github.com/ClementTsang/bottom) ⭐ 13,924 | 🐛 109 | 🌐 Rust | 📅 2026-08-24 - Yet another cross-platform graphical process/system monitor.
* [bashtop](https://github.com/aristocratos/bashtop) ⭐ 11,118 | 🐛 64 | 🌐 Shell | 📅 2023-08-21 - Resource monitor that shows usage and stats for processor, memory, disks, network, and processes.
* [nvtop](https://github.com/Syllo/nvtop) ⭐ 10,936 | 🐛 146 | 🌐 C | 📅 2026-05-06 - A top like task monitor for AMD, Intel and NVIDIA GPUs, that can handle multiple GPUs and print information about them in a htop-familiar way.
* [bpytop](https://github.com/aristocratos/bpytop) ⭐ 10,920 | 🐛 99 | 🌐 Python | 📅 2025-06-01 - Linux/macOS/FreeBSD resource monitor with a nice interface.
* [gtop](https://github.com/aksakalli/gtop) ⭐ 9,929 | 🐛 40 | 🌐 JavaScript | 📅 2025-11-06 - System monitoring dashboard for terminal written in Node.js.
* [nvitop](https://github.com/XuehaiPan/nvitop) ⭐ 7,120 | 🐛 19 | 🌐 Python | 📅 2026-07-27 - An interactive NVIDIA-GPU process viewer and beyond, the one-stop solution for GPU process management.
* [procs](https://github.com/dalance/procs) ⭐ 6,142 | 🐛 41 | 🌐 Rust | 📅 2026-08-17 - A modern replacement for ps written in Rust.
* [s-tui](https://github.com/amanusk/s-tui) ⭐ 5,068 | 🐛 39 | 🌐 Python | 📅 2026-08-19 - Stress-Terminal UI, s-tui, monitors CPU temperature, frequency, power, and utilization in a graphical way from the terminal.
* [gputop](https://github.com/wookayin/gpustat) ⭐ 4,392 | 🐛 30 | 🌐 Python | 📅 2026-05-30 - A simple command-line utility for querying and monitoring GPU status.
* [vtop](https://github.com/MrRio/vtop) ⭐ 4,173 | 🐛 80 | 🌐 JavaScript | 📅 2020-10-08 - Alternative to top with several additional stats.
* [gotop](https://github.com/xxxserxxx/gotop) ⭐ 3,092 | 🐛 90 | 🌐 Go | 📅 2026-05-07 - A terminal based graphical activity monitor inspired by gtop and vtop.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,043 | 🐛 42 | 🌐 Rust | 📅 2026-08-24 - Sort of like top or htop but with zoom-able charts, CPU, GPU, network, and disk usage
* [below](https://github.com/facebookincubator/below) ⭐ 2,492 | 🐛 34 | 🌐 Rust | 📅 2026-08-24 - A time traveling resource monitor for modern Linux systems
* [tiptop](https://github.com/nschloe/tiptop) ⭐ 2,124 | 🐛 25 | 🌐 Python | 📅 2025-09-04 - A command-line system monitoring tool in the spirit of top, written in Python. It displays various interesting system stats and graphs them. Works on all operating systems.
* [amdgpu-top](https://github.com/Umio-Yasuno/amdgpu_top) ⭐ 1,681 | 🐛 5 | 🌐 Rust | 📅 2026-08-22 - A tool that display AMD GPU utilization and information, gathered from performance counters (GRBM, GRBM2), sensors, fdinfo, and AMDGPU driver.
* [radeontop](https://github.com/clbr/radeontop) ⭐ 914 | 🐛 50 | 🌐 C | 📅 2026-03-20 - View your AMD GPU utilization, both for the total activity percent and individual blocks.
* [ttop](https://github.com/inv2004/ttop) ⭐ 394 | 🐛 6 | 🌐 Nim | 📅 2026-08-16 - top-like system monitoring tool with TUI, historical data service and triggers.
* [PCtrl](https://github.com/MohamedSherifNoureldin/PCtrl) ⭐ 122 | 🐛 6 | 🌐 Rust | 📅 2023-05-15 - Robust, featureful, easy-to-use and powerful process manager.
* [tegratop](https://github.com/pythops/tegratop) ⭐ 85 | 🐛 1 | 🌐 Rust | 📅 2025-12-14 - TUI monitoring tool (top like) for Nvidia Jetson boards.
* [vitals](https://github.com/AngelJumbo/vitals) ⭐ 35 | 🐛 0 | 🌐 C | 📅 2026-01-19 - System usage visualizer and top replacement for Linux.
* [TTV](https://github.com/caio-ishikawa/term-task-viewer) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2023-08-27 - terminal-task-viewer: a lightweight terminal tool to manage processes in Unix machines.
* [pshunt](https://github.com/jamesma100/pshunt) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2025-07-15 - Process viewer similar to htop (view, search and kill processes and vi keybindings).
* [atop](https://www.atoptool.nl/index.php) - Atop is TUI performance monitor for Linux; it reports the activity of all processes (even if processes have finished during the interval), daily logging of system and process activity for long-term analysis, overloaded system resources, etc.
* [htop](http://hisham.hm/htop/) - An interactive process viewer for Unix; improves the UI of `top`, by adding real-time meters and colors.
* [iotop](http://guichaz.free.fr/iotop/) - "A Python program with a top like UI used to show of behalf of which process is the I/O going on".
* [nmon](https://nmon.sourceforge.io/pmwiki.php) - Nigel's performance Monitor for Linux.
* [top](https://gitlab.com/procps-ng/procps) - The classical Unix utility that provides a rolling display of top CPU using processes.

## <a name="file-dir-cleanup"></a>Clean up of files and directories

Find/remove duplicate files, automatically organize files, etc..

* [FClones](https://github.com/pkolaczk/fclones) ⭐ 2,913 | 🐛 102 | 🌐 Rust | 📅 2025-03-03 - Efficient Duplicate File Finder.
* [rmlint](https://github.com/sahib/rmlint) ⭐ 2,410 | 🐛 128 | 🌐 C | 📅 2026-08-21 - Recursively scan a directory tree looking for duplicate and broken files; it outputs statistics and save the list of files in JSON format and produces a shell script that can be inspected before running it to delete the desire files.
* [classifier](https://github.com/bhrigu123/classifier) ⭐ 1,099 | 🐛 25 | 🌐 Python | 📅 2022-03-07 - Organize files in your current directory, by classifying them into folders of music, PDFs, images, etc.
* [detox](https://github.com/dharple/detox) ⚠️ Archived - Easily clean up filenames; it replaces characters like spaces with standard equivalents and UTF-8 or Latin-1 (or CP 1252) characters with more handy ones.
* [organize-cli](https://github.com/ManrajGrover/organize-cli) ⭐ 371 | 🐛 7 | 🌐 JavaScript | 📅 2018-10-11 - Organize your files automatically.
* [Framed](https://github.com/mactat/framed) ⭐ 181 | 🐛 1 | 🌐 Go | 📅 2026-05-30 - A CLI tool that simplifies the organization and management of files and directories in a reusable and architectural manner.
* [backdown](https://github.com/Canop/backdown) ⭐ 146 | 🐛 3 | 🌐 Rust | 📅 2026-06-18 - Safely and ergonomically remove duplicate files
* [doggo](https://github.com/0nsh/doggo) ⭐ 52 | 🐛 5 | 🌐 Python | 📅 2025-07-14 - CLI tool that uses AI to help you search for and organize images using natural language queries (instead of remembering filenames, you can describe what you're looking for).
* [inventory](https://github.com/mothdotmonster/inventory) ⭐ 51 | 🐛 0 | 🌐 Shell | 📅 2022-04-19 - Move files like an old text adventure.
* [image-sorter](https://github.com/jgalat/image-sorter) ⭐ 48 | 🐛 0 | 🌐 Rust | 📅 2024-12-27 - Terminal user interface for sorting images using key bindings written in Rust; It requires w3m to render the images.
* [smash](https://github.com/thushan/smash) ⭐ 20 | 🐛 10 | 🌐 Go | 📅 2026-01-30 - Smash through to find duplicate files super fast by slicing files intelligently.
* [Dext](https://github.com/AfzGit/dext) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2026-08-16 - (Directories by Extensions) is a script that moves (or copies) files of the same extension into a folder.
* [Duplito](https://github.com/ftarlao/duplito) ⭐ 9 | 🐛 3 | 🌐 Go | 📅 2025-08-01 - Command-line tool designed to help you identify duplicate file on your system by listing the files in folders like ls does and highlighting what is duplicate.
* [duple](https://github.com/dbruce-ae05/duple) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-02-11 - Find and remove duplicate files.
* [czkawka](https://qarmin.github.io/czkawka/) - Remove unnecessary files from your computer
* [mat2](https://0xacab.org/jvoisin/mat2.git) - Metadata removal tool, supporting a wide range of commonly used file formats.
* [NTC](https://codeberg.org/ItsZariep/ntc) - A program that, based on the contents of a folder, create tabs (subfolders inside the selected folder) and displays their contents.

# <a name="File-and-Filesystem-Management"></a>File and Filesystem Management

## <a name="file-manager"></a>File managers

Applications for interactively managing files and directories.

* [Yazi](https://github.com/sxyazi/yazi) ⭐ 41,646 | 🐛 65 | 🌐 Rust | 📅 2026-08-24 - Blazing fast terminal file manager written in Rust, based on async I/O.
* [superfile](https://github.com/yorukot/superfile) ⭐ 22,788 | 🐛 258 | 🌐 Go | 📅 2026-08-20 - Pretty fancy and modern file manager.
* [nnn](https://github.com/jarun/nnn) ⭐ 21,828 | 🐛 5 | 🌐 C | 📅 2026-08-17 - "The unorthodox terminal file manager" - a tiny, nearly 0-config and fast file manager supporting all the operations on files and directories.
* [lf](https://github.com/gokcehan/lf) ⭐ 9,477 | 🐛 81 | 🌐 Go | 📅 2026-08-25 - lf (as in "list files") is a terminal file manager written in Go with a heavy inspiration from ranger file manager.
* [joshuto](https://github.com/kamiyaa/joshuto) ⭐ 3,723 | 🐛 103 | 🌐 Rust | 📅 2026-08-20 - ranger-like terminal file manager
* [walk](https://github.com/antonmedv/walk) ⭐ 3,633 | 🐛 10 | 🌐 Go | 📅 2026-01-06 - Terminal file manager.
* [Far2l](https://github.com/elfmz/far2l) ⭐ 2,210 | 🐛 477 | 🌐 C++ | 📅 2026-08-24 - Linux port of Far v2 file manager.
* [clifm](https://github.com/leo-arch/clifm) ⭐ 1,721 | 🐛 26 | 🌐 C | 📅 2026-08-22 - A CLI-based, shell-like, and non-curses terminal file manager written in C: simple, fast, extensible, and lightweight as hell.
* [hunter](https://github.com/rabite0/hunter) ⭐ 1,337 | 🐛 40 | 🌐 Rust | 📅 2022-09-26 - Ranger-like file browser written in rust.
* [felix](https://github.com/kyoheiu/felix) ⭐ 915 | 🐛 29 | 🌐 Rust | 📅 2025-04-12 - TUI file manager with vim-like key mapping
* [TUIFI Manager](https://github.com/GiorgosXou/TUIFIManager) ⭐ 826 | 🐛 15 | 🌐 Python | 📅 2026-06-30 - A cross-platform terminal-based termux-oriented file manager (and component), meant to be used with a Uni-Curses project or as is.
* [cfiles](https://github.com/mananapr/cfiles) ⭐ 508 | 🐛 22 | 🌐 C | 📅 2021-08-28 - ncurses file manager written in C with vim like keybindings
* [projectable](https://github.com/dzfrias/projectable) ⭐ 460 | 🐛 11 | 🌐 Rust | 📅 2025-05-28 - A TUI file manager built for projects.
* [goful](https://github.com/anmitsu/goful) ⭐ 380 | 🐛 4 | 🌐 Go | 📅 2021-11-29 - Goful is a CUI file manager written in Go.
* [fman](https://github.com/nore-dev/fman) ⭐ 339 | 🐛 7 | 🌐 Go | 📅 2022-11-28 - TUI File Manager
* [sfm](https://github.com/afify/sfm) ⭐ 259 | 🐛 6 | 🌐 C | 📅 2025-11-14 - Simple file manager for unix-like systems with kernel event notifications, monitoring filesystem events, dual pane and more.
* [fzfm](https://github.com/ashish0kumar/fzfm) ⭐ 210 | 🐛 4 | 🌐 Shell | 📅 2025-08-04 - A command-line fuzzy finder file manager.
* [adbtuifm](https://github.com/darkhz/adbtuifm) ⭐ 189 | 🐛 3 | 🌐 Go | 📅 2022-03-16 - A TUI file manager for the Android Debug Bridge, to make transfers between the device and client easier.
* [Better tree](https://github.com/LeperGnome/bt) ⭐ 166 | 🐛 15 | 🌐 Go | 📅 2026-05-20 - Interactive tree-like terminal file manager.
* [fml](https://github.com/wick3dr0se/fml) ⭐ 106 | 🐛 0 | 🌐 Shell | 📅 2024-02-03 - Simple and fast file manager written in BASH.
* [ncursesFM](https://github.com/FedeDP/ncursesFM) ⭐ 90 | 🐛 3 | 🌐 C | 📅 2019-01-21 - File manager written in C, rather complete in terms of features, especially lightweight and responsive.
* [RTFM](https://github.com/isene/RTFM) ⭐ 58 | 🐛 0 | 🌐 Ruby | 📅 2026-05-19 - Feature-rich Terminal File Manager written in Ruby.
* [veld](https://github.com/BranBushes/veld-fm) ⭐ 29 | 🐛 4 | 🌐 Python | 📅 2025-11-13 - A modern, tileable, terminal-based file manager built with Python and Textual.
* [lfm](https://inigo.katxi.org/devel/lfm/) - (Last File Manager) - a file manager written in Python; it comes with lots of features, including 1-pane or 2-pane view, files filters and bookmarks, tree view, virtual file-systems to open compressed archives, search in files, customizable keybindings and themes.
* [Midnight Commander](http://www.midnight-commander.org/) - A visual file manager, full-screen text mode application that allows you to copy, move and delete files and whole directory trees and search for files; includes an internal viewer and editor.
* [ranger](https://ranger.github.io/) - File manager with vi key bindings, curses interface with a view on the directory hierarchy, comes with a file launcher that automatically determines which program to use for opening a given file type.
* [vifm](https://vifm.info/) - "ncurses based file manager with vi like keybindings/modes/options/commands/configuration, which also borrows some useful ideas from mutt" (cit.).

## <a name="file-explorer"></a>File explorer and tree visualization

Show directory trees and navigate through the file system (but not full-featured file managers).

* [xplr](https://github.com/sayanarijit/xplr) ⭐ 4,810 | 🐛 15 | 🌐 Rust | 📅 2026-08-17 - A hackable, minimal, fast TUI file explorer, stealing ideas from nnn and fzf.
* [tere](https://github.com/mgunyho/tere) ⭐ 1,801 | 🐛 16 | 🌐 Rust | 📅 2026-03-09 - Terminal file explorer that is a faster alternative to using cd and ls to browse folders in your terminal.
* [tre](https://github.com/dduan/tre) ⭐ 1,216 | 🐛 23 | 🌐 Rust | 📅 2024-09-03 - `tree` command improved with git awareness, editor aliasing, and colors.
* [browsr](https://github.com/juftin/browsr) ⭐ 644 | 🐛 13 | 🌐 Python | 📅 2026-04-22 - A pleasant file explorer that can browse the contents of local and remote filesystems with your keyboard or mouse; remotes include GitHub, over SSH, in AWS S3, Google Cloud Storage, or Azure Blob Storage.
* [twf](https://github.com/wvanlint/twf) ⭐ 292 | 🐛 8 | 🌐 Go | 📅 2021-12-03 - Standalone tree view file explorer.
* [alder](https://github.com/aweary/alder) ⭐ 250 | 🐛 3 | 🌐 JavaScript | 📅 2017-06-20 - Directory tree visualizer.
* [kupo](https://github.com/darrenburns/kupo) ⭐ 212 | 🐛 4 | 🌐 Python | 📅 2024-07-05 - A terminal file browser, kupo!
* [ictree](https://github.com/NikitaIvanovV/ictree) ⭐ 170 | 🐛 6 | 🌐 C | 📅 2024-03-26 - Like tree but interactive.
* [Rust-Traverse](https://github.com/dmcg310/Rust-Traverse) ⭐ 84 | 🐛 0 | 🌐 Rust | 📅 2025-04-23 - Rust traverse is a terminal based file explorer. It is inspired by the NNN file manager. It uses Ratatui for the terminal UI, with Crossterm for the terminal backend.
* [Hop!](https://github.com/benrutter/hop) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2023-08-11 - File explorer designed to be fast, simple and user-friendly, running on any operating system.
* [tree](http://mama.indstate.edu/users/ice/tree/) - Recursive directory listing command that produces a depth indented list of files.

## <a name="file-handling"></a>File and file system handling

Tools for managing files and directories (copy, move, extraction from compressed archives, change permissions, etc.).

* [progress](https://github.com/Xfennec/progress) ⭐ 8,858 | 🐛 66 | 🌐 C | 📅 2024-11-19 - Monitor the progress of common Coreutils command-line tools (`cp`, `mv`, `dd`, `tar`, `rsync`, etc.); it uses a ncurses interface to display the percentage of data copied; it works by reading from system files and retrieving the necessary information for the estimation.
* [doxx](https://github.com/bgreenwell/doxx) ⭐ 3,745 | 🐛 8 | 🌐 Rust | 📅 2026-08-10 - Terminal native document viewer for Word files (view, search and export documents).
* [ouch](https://github.com/ouch-org/ouch) ⭐ 3,722 | 🐛 103 | 🌐 Rust | 📅 2026-08-24 - Painless compression and decompression in the terminal.
* [logrotate](https://github.com/logrotate/logrotate) ⭐ 1,545 | 🐛 64 | 🌐 C | 📅 2026-08-01 - Rotate, compress and mail logs.
* [xcp](https://github.com/tarka/xcp) ⭐ 927 | 🐛 18 | 🌐 Rust | 📅 2026-06-23 - Extended cp.
* [compsize](https://github.com/kilobyte/compsize) ⭐ 412 | 🐛 22 | 🌐 C | 📅 2023-12-25 - Find compression type/ratio on a file or set of files on a btrfs file system.
* [qcp](https://github.com/crazyscot/qcp) ⭐ 284 | 🐛 11 | 🌐 Rust | 📅 2026-08-01 - Quick File Copy using QUIC.
* [vidir](https://github.com/trapd00r/vidir) ⭐ 227 | 🐛 7 | 🌐 Perl | 📅 2024-06-08 - vidir allows editing of the contents of a directory in a text editor.
* [symlinks](https://github.com/brandt/symlinks) ⭐ 156 | 🐛 11 | 🌐 C | 📅 2021-09-24 - Symlinks is a simple tool that helps find and remedy problematic symbolic links on a system.
* [pycp](https://github.com/dmerejkowsky/pycp) ⭐ 151 | 🐛 10 | 🌐 Python | 📅 2024-03-20 - cp and mv with a progress bar.
* [unix-permissions](https://github.com/ehmicky/unix-permissions) ⭐ 144 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-11 - Swiss Army knife for Unix permissions.
* [file-type-cli](https://github.com/sindresorhus/file-type-cli) ⭐ 88 | 🐛 0 | 🌐 JavaScript | 📅 2021-11-24 - Detect the file type of a file or stdin.
* [ForkFS](https://github.com/SUPERCILEX/forkfs) ⭐ 86 | 🐛 1 | 🌐 Rust | 📅 2025-03-12 - ForkFS allows you to sandbox a process's changes to your file system.
* [lib-x](https://github.com/Benexl/lib-x) ⭐ 75 | 🐛 0 | 🌐 Shell | 📅 2026-08-24 - Browse your calibre library from the terminal.
* [conan](https://github.com/mirage/conan) ⭐ 59 | 🐛 3 | 🌐 OCaml | 📅 2026-03-06 - Find clue about the type of the file.
* [choof](https://github.com/elParadigm/choof) ⭐ 36 | 🐛 1 | 🌐 Go | 📅 2025-04-14 - Choof is a fast and minimal CLI tool for managing files, built with Bubble Tea for Linux.
* [fstk](https://github.com/archsyscall/fstk) ⭐ 31 | 🐛 2 | 🌐 Rust | 📅 2025-03-18 - Stack-based file & directory manager: modern "cut/paste" alternative to mv.
* [Snoop](https://github.com/Mandrew0822/Snoop) ⭐ 29 | 🐛 0 | 🌐 C++ | 📅 2023-08-08 - A command-line utility for Linux that provides information about files in a directory.
* [zip-stream-cli](https://github.com/alexandre-garrec/zip-stream-cli) ⭐ 25 | 🐛 1 | 🌐 JavaScript | 📅 2024-09-16 - A tool that allows to stream and display the contents of various file types from a remote ZIP archive directly in your terminal. With support for images, audio files, text, PDFs, and more,
* [burf](https://github.com/razeghi71/burf) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-02-02 - TUI for Google Cloud Storage (GCS).
* [gcp](https://github.com/aelafifi/gcp) ⭐ 18 | 🐛 2 | 🌐 Python | 📅 2019-07-21 - (Goffi's cp) - an advanced file copier tool, heavily inspired from the traditional `cp` command, but with some additional features: Displays the copy progress indicator, with estimated time, current file speed; logs of all actions; resume of interrupted copy processes.
* [dlorg](https://github.com/deepspeccode/dlorg) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2024-08-17 - Powerful and intuitive that automatically organizes your cluttered Downloads folder into a neatly structured directory system.
* [doppelganger](https://github.com/witchard/doppelganger) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2021-07-18 - Save and load your shell environment to create doppelganger shells!
* [gcstree](https://github.com/owlinux1000/gcstree) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2025-09-15 - Tree command for GCS (Google Cloud Storage).
* [Fast Files](https://github.com/mintycube/fast-files) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-06-04 - ff is a bash script which is a combination of `mkdir` and `touch`. It can create directory structures and files simultaneously and lists the created objects using `eza`, `lsd`, or `ls`.
* [CHMpy-sp](https://github.com/AmmarSyamil/CHMpy) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-08-07 - TUI made from Textual for changing file/folder permission in Linux.
* [treegen](https://github.com/bilbilak/treegen) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2026-06-11 - ASCII tree directory and file structure generator.
* [dtrx](https://brettcsmith.org/2007/dtrx/) - (Do The Right eXtraction) aims at taking "all the hassle out of extracting archives"; allows using one command to extract archives in different formats, recursive extraction (files into file) and extracts files into dedicated directories.
* [PathPicker](https://facebook.github.io/PathPicker/) - A tool from Facebook that parses the output from a command and presents a UI to select files and directories, can be used to apply a command of a interactively selected files or to move across directories.
* [TUI Archiver](https://www.nexus0.net/pub/sw/tuiarchiver/) - A TUI/CLI application to list / manage archives. Can be used stand-alone and has some features for integrating with TUI file managers

## <a name="backup"></a>Backup

Tools to manage the backup of files and directories.

* [shallow-backup](https://github.com/alichtman/shallow-backup) ⭐ 1,335 | 🐛 23 | 🌐 Python | 📅 2026-03-21 - Git integrated backup tool.
* [bupstash](https://github.com/andrewchambers/bupstash) ⭐ 924 | 🐛 139 | 🌐 Rust | 📅 2024-02-16 - Secure, encrypted backups with efficient deduplication, client-side encryption, offline decryption, search-tagged data protection, strong privacy, robust performance on slow networks, memory-safe security against attacks, incremental backups, and minimal RAM usage for production use.
* [paperbackup](https://github.com/intra2net/paperbackup) ⭐ 145 | 🐛 13 | 🌐 Python | 📅 2024-03-18 - Create a PDF with barcodes to backup text files on paper.
* [backhub](https://github.com/Tanq16/backhub) ⭐ 73 | 🐛 0 | 🌐 Go | 📅 2025-08-03 - Backhub helps maintain backups of multiple GitHub repos as full local mirrors.
* [Zaloha.sh](https://github.com/Fitus/Zaloha.sh) ⭐ 67 | 🐛 3 | 🌐 Shell | 📅 2021-03-03 - Shellscript for synchronization of files and directories.
* [thread-safe](https://github.com/dkaslovsky/thread-safe) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2023-01-30 - Keep your favorite Twitter threads safe with a local copy.
* [gwbackupy](https://github.com/smartondev/gwbackupy) ⭐ 50 | 🐛 14 | 🌐 Python | 📅 2026-03-09 - Open source Google Workspace™ backup solution.
* [qbak](https://github.com/andreas-glaser/qbak) ⭐ 6 | 🐛 4 | 🌐 Rust | 📅 2026-02-09 - A single-command backup helper for Linux and POSIX systems written in Rust; The program creates timestamped backup copies of files and directories with zero configuration.
* [autorestic](https://autorestic.vercel.app/) - A wrapper around the [restic](https://restic.net/) backup tool, with the goal of simplifying the setup and usage through the use of config files.
* [borg](https://www.borgbackup.org/) - Encrypted backups with a clean and simple interface, easy to use and set up, possibility to mount the backup archive with FUSE and inspect it as a regular file system.
* [bup](https://bup.github.io/) - Very efficient backup system based on the git packfile format, providing fast incremental saves and global deduplication.
* [Crestic](https://nils-werner.github.io/crestic/) - Configurable Restic Wrapper.
* [duplicity](http://duplicity.nongnu.org/) - Creates GPG encrypted, compressed backups; client-side encryption allows uploading the backup onto untrusted servers.
* [Duply](http://duply.net/) - Simplifies the use of [duplicity](http://duplicity.nongnu.org/) by keeping clean configuration files to automate the backup.
* [Kopia](https://kopia.io/) - Cross-platform backup tool for Windows, macOS & Linux with fast, incremental backups, client-side end-to-end encryption, compression, and data deduplication. CLI and GUI included.
* [rdiff-backup](https://rdiff-backup.net/) - Reverse differential backup tool, over a network or locally, using the same protocol as rsync to transfer and store data.
* [Restic](https://restic.net/) - A backup program that is fast, efficient, and secure.
* [rsnapshot](https://rsnapshot.org) -  A filesystem snapshot utility based on rsync. It manages a rotation schedule when to discard older backup, e.g. from hourly to yearly. The Perl code makes extensive use of hard links and greatly reduces the disk space required.
* [zbackup](http://zbackup.org/) - A globally-deduplicating backup tool, based on the ideas found in rsync.
* [ZnapZend](https://www.znapzend.org) - ZFS centric backup tool creates snapshots and sends them to backup volumes. It manages local and remote copies by thinning them out as time progresses.

## <a name="file-watch"></a>File watching for changes

Services that watch files for changes and perform actions when something happens.

* [watchexec](https://github.com/watchexec/watchexec) ⭐ 7,130 | 🐛 36 | 🌐 Rust | 📅 2026-08-24 - Executes commands in response to file modifications.
* [Viddy](https://github.com/sachaos/viddy) ⭐ 5,402 | 🐛 33 | 🌐 Rust | 📅 2026-08-16 - Modern watch command. Time machine and pager etc.
* [reflex](https://github.com/cespare/reflex) ⭐ 3,551 | 🐛 28 | 🌐 Go | 📅 2026-02-26 - Reflex is a small tool to watch a directory and rerun a command when certain files change.
* [Chokidar CLI](https://github.com/open-cli-tools/chokidar-cli) ⭐ 873 | 🐛 40 | 🌐 JavaScript | 📅 2025-09-22 - Fast cross-platform command line utility to watch file system changes.
* [fswatch](https://github.com/codeskyblue/fswatch) ⭐ 348 | 🐛 2 | 🌐 Go | 📅 2025-12-01 - Watch file change, and trigger commands (cross platform).
* [rwatch](https://github.com/davidhfrankelcodes/rwatch) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2026-05-25 - A Rust re-implementation of the classic Unix watch command that allows you to run a command repeatedly and watch its output.
* [wfh](https://github.com/kzys/wfh) ⭐ 14 | 🐛 11 | 🌐 Rust | 📅 2023-02-06 - Continuously watches your local directories and rsync them against a remote host.
* [watcher](https://github.com/sethigeet/watcher) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2022-03-25 - Watches all the files present in a directory and whenever a file is changed or a file is created/deleted from the directory, it runs a specified command.

## <a name="file-renamer"></a>File renamers

Utilities to rename files and directories: address multiple items with one command, interactively edit the name within an editor, etc..

* [F2](https://github.com/ayoisaiah/f2) ⭐ 2,436 | 🐛 4 | 🌐 Go | 📅 2026-06-22 - Cross-platform command-line tool for batch renaming files and directories quickly and safely.
* [massren](https://github.com/laurent22/massren) ⭐ 1,396 | 🐛 13 | 🌐 Go | 📅 2024-12-08 - Easily rename multiple files using your text editor.
* [mmv](https://github.com/itchyny/mmv) ⭐ 806 | 🐛 0 | 🌐 Go | 📅 2023-04-26 - Rename multiple files using your $EDITOR. The command name is named after multi-mv.
* [nomino](https://github.com/yaa110/nomino) ⭐ 709 | 🐛 6 | 🌐 Rust | 📅 2025-08-07 - Batch rename utility for developers.
* [rename-cli](https://github.com/jhotmann/node-rename-cli) ⚠️ Archived - File renamer with TUI interface and preview.
* [Musort](https://github.com/tdeerenberg/Musort) ⭐ 89 | 🐛 1 | 🌐 Python | 📅 2025-07-09 - Rename multiple audio/music files based on the ID3 tag at once.
* [Ren](https://github.com/robenkleene/ren-find) ⭐ 65 | 🐛 0 | 🌐 Rust | 📅 2026-02-22 - Ren is a command-line utility that takes find-formatted lines via standard input, and batch renames them.
* [VisioNomicon](https://github.com/rehanzo/VisioNomicon) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2025-01-07 - A utility that leverages GPT-4V to rename image files based on their content.
* [moove](https://github.com/urin/moove) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-07-19 - Manipulate file names and locations using a text editor.
* [mmv-c](https://github.com/mcauley-penney/mmv-c) ⭐ 14 | 🐛 5 | 🌐 C | 📅 2025-12-27 - Interactively rename files with your favorite editor.
* [Tempren](https://github.com/idle-code/tempren) ⭐ 12 | 🐛 33 | 🌐 Python | 📅 2026-08-17 - A powerful file renaming utility that uses flexible template expressions to create new file paths and names.
* [Bren](https://www.byteptr.com/bren/) - Bren is a command line tool for GNU/Linux (and many others). It has support for GNU Guile scripting. Bren is simple, fast, and it's written in C.
* [rename](https://www.kernel.org/pub/linux/utils/util-linux/) - Included in `util-linux`, allows bulk rename of files with regex support.
* [renamed.to](https://www.renamed.to/cli) - AI-powered file renamer that analyzes document content (PDFs, scans, images) and generates descriptive filenames in bulk.
* [renameutils](http://www.nongnu.org/renameutils/) - A set of programs to change file and directory names by editing them in-place, I find `imv` especially useful to edit a filename at the program prompt.

## <a name="file-system"></a>File systems

File systems with specific features; e.g., the possibility to add tags and labels to files.

* [sshfs](https://github.com/libfuse/sshfs) ⭐ 7,633 | 🐛 61 | 🌐 C | 📅 2026-08-08 - Locally mount a remote file-system through SSH and access files and directory as they would be on the local machine.
* [ipfs-deploy](https://github.com/ipfs-shipyard/ipfs-deploy) ⭐ 1,168 | 🐛 31 | 🌐 JavaScript | 📅 2025-05-10 - Zero-Config CLI to Deploy Static Websites to IPFS [IPFS](https://en.wikipedia.org/wiki/InterPlanetary_File_System).
* [wutag](https://github.com/vv9k/wutag) ⭐ 44 | 🐛 6 | 🌐 Rust | 📅 2022-09-29 - CLI Tool for tagging and organizing files by tags.
* [TMSU](http://tmsu.org/) - A simple tool for tagging files, providing a virtual filesystem for a tag-based view of your files from within any other program.

## <a name="conversion"></a>File format converters

Utilities to convert different types of files.

* [MarkItDown](https://github.com/microsoft/markitdown) ⭐ 176,038 | 🐛 890 | 🌐 Python | 📅 2026-08-19 - Python tool for converting files and office documents to Markdown.
* [unoserver](https://github.com/unoconv/unoserver) ⭐ 930 | 🐛 9 | 🌐 Python | 📅 2026-06-10 - Using LibreOffice as a server for converting documents, it allows converting multiple documents without loading libreoffice into memory every time.
* [hget](https://github.com/bevacqua/hget) ⭐ 389 | 🐛 0 | 🌐 HTML | 📅 2024-03-16 - A CLI to convert HTML into plain text. Can be used to fetch a site's HTML version and convert it into plain text, or to deliver plain text versions of your site dynamically.
* [markdrop](https://github.com/shoryasethia/markdrop) ⭐ 210 | 🐛 8 | 🌐 Python | 📅 2026-08-09 - Converts PDFs to markdown while extracting images and tables, generating descriptive text descriptions for extracted tables/images using several LLM clients.
* [lx](https://github.com/rasros/lx) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2026-07-29 - Convert arbitrary files into Markdown-fenced blocks for LLM context.
* [Vertopal-CLI](https://github.com/vertopal/vertopal-cli) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2025-11-27 - Vertopal-CLI is a small, yet powerful utility for converting digital files to a variety of file formats using Vertopal public API.
* [NestedTextTo](https://github.com/AndydeCleyre/nestedtextto) ⭐ 23 | 🐛 4 | 🌐 Python | 📅 2026-08-24 - CLI to convert between NestedText and JSON, YAML, or TOML.
* [simtex](https://github.com/simtex-dev/engine) ⭐ 20 | 🐛 17 | 🌐 Python | 📅 2022-11-21 - simtex (simplified LaTeX) allows you to convert your Markdown or text lectures into LaTeX file with one command, configured with simple .json file.
* [jsonify-resume](https://github.com/ashishbinu/jsonify-resume) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2023-08-24 - A CLI that converts resumes into JSON Resume schema.
* [antiword](https://web.archive.org/web/20071002133135/http://www.winfield.demon.nl/) - Reader and converted for the proprietary MS .doc file format.
* [BaFi](https://mmalcek.github.io/bafi/) - Universal JSON, BSON, YAML, CSV, XML translator to ANY format using templates.
* [catdoc](http://www.wagner.pp.ru/~vitus/software/catdoc/) - Convert Microsoft Word files to plain text; output is sent to the standard output.
* [hecat](https://gitlab.com/nodiscc/hecat) - A generic automation tool around data stored as plain-text YAML files.
* [Pandoc](http://pandoc.org/) - Universal document file converter; handles input output from/to a number of formats: HTML, PDF, LaTeX, DOCX, ODT, AsciiDoc, Markdown, Textile, just to mention a few; the quality of conversion strongly depends on the combination of input/output formats.
* [scss-to-css](https://github.com/adamlui/scss-to-css/#readme) - Recursively compile all SCSS files into minified CSS.
* [transflac](https://bitbucket.org/gbcox/transflac.git/) - A repository containing a series of utilities to assist in the maintenance and organization of FLAC based music collections.
* [wv](https://wvware.sourceforge.net/) - Utility for performing operations on .doc files. The tool is now deprecated in favor of AbiWord, which uses the same library that is used in the CLI program.

# <a name="Text-and-Data-Processing"></a>Text and Data Processing

## <a name="text-processing"></a>Text processing

Text processing utilities to cut or sort lines, find dead links, colorize command output, etc..

* [espanso](https://github.com/espanso/espanso) ⭐ 14,347 | 🐛 535 | 🌐 Rust | 📅 2026-08-24 - Cross-platform Text Expander written in Rust. Not limited to the command line.
* [Ultimate Plumber](https://github.com/akavel/up) ⭐ 8,836 | 🐛 30 | 🌐 Go | 📅 2024-09-05 - Helps to interactively and incrementally explore textual data in Linux, by making it easier to quickly build complex pipelines, thanks to a fast feedback loop.
* [pup](https://github.com/ericchiang/pup) ⭐ 8,434 | 🐛 106 | 🌐 HTML | 📅 2024-05-02 - Parsing HTML at the command line.
* [lolcat](https://github.com/busyloop/lolcat) ⭐ 6,564 | 🐛 33 | 🌐 Ruby | 📅 2024-03-05 - Ruby Gem to colorize the output of the cat command.
* [toolong](https://github.com/Textualize/toolong) ⭐ 3,939 | 🐛 37 | 🌐 Python | 📅 2024-08-05 - A terminal application to view, tail, merge, and search log files (plus JSONL).
* [rich](https://github.com/Textualize/rich-cli) ⭐ 3,712 | 🐛 46 | 🌐 Python | 📅 2026-08-12 - Rich-CLI is a command line toolbox for fancy output in the terminal, built with [Rich](https://github.com/Textualize/rich) ⭐ 57,192 | 🐛 373 | 🌐 Python | 📅 2026-06-23.
* [trurl](https://github.com/curl/trurl) ⭐ 3,347 | 🐛 5 | 🌐 Perl | 📅 2026-07-16 - Command line tool for URL parsing and manipulation.
* [yek](https://github.com/bodo-run/yek) ⭐ 2,473 | 🐛 12 | 🌐 Rust | 📅 2026-06-29 - A fast Rust based tool to serialize text-based files in a repository or directory for LLM consumption.
* [choose](https://github.com/theryangeary/choose) ⭐ 2,265 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk.
* [awk](https://github.com/onetrueawk/awk) ⭐ 2,221 | 🐛 15 | 🌐 C | 📅 2026-08-19 - A historical, general-purpose text file processor, implements a domain-specific language designed for text processing and typically used as a data extraction and reporting tool.
* [anew](https://github.com/tomnomnom/anew) ⭐ 1,656 | 🐛 9 | 🌐 Go | 📅 2024-01-12 - Tool for adding new lines to files, skipping duplicates.
* [tuc](https://github.com/riquito/tuc) ⭐ 821 | 🐛 8 | 🌐 Rust | 📅 2026-08-01 - You want to cut on more than just a character, perhaps using negative indexes or format the selected fields as you want... Maybe you want to cut on lines (ever needed to drop first and last line?)... That's where tuc can help.
* [hck](https://github.com/sstadick/hck) ⭐ 743 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut clone.
* [as-tree](https://github.com/jez/as-tree) ⭐ 503 | 🐛 19 | 🌐 Rust | 📅 2021-10-07 - Print a list of paths as a tree of paths.
* [brok](https://github.com/smallhadroncollider/brok) ⭐ 422 | 🐛 13 | 🌐 Haskell | 📅 2023-03-06 - Find broken links in text documents.
* [gtree](https://github.com/ddddddO/gtree) ⭐ 358 | 🐛 38 | 🌐 Go | 📅 2026-08-21 - Using either Markdown or programmatically to generate directory trees and directories, and to verify directories.
* [rare](https://github.com/zix99/rare) ⭐ 356 | 🐛 2 | 🌐 Go | 📅 2026-02-08 - Real-time regex-extraction and aggregation into common formats such as histograms, bar graphs, numerical summaries, tables, and more!
* [huniq](https://github.com/koraa/huniq) ⭐ 265 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Command line utility to remove duplicates from the given input. Note that huniq does not sort the input, it just removes duplicates.
* [trre](https://github.com/c0stya/trre) ⭐ 257 | 🐛 2 | 🌐 C | 📅 2025-09-25 - Transductive regular expressions: an extension of the regular expressions for text editing and a grep-like command line tool.
* [wg-cmd](https://github.com/AndrianBdn/wg-cmd) ⭐ 223 | 🐛 2 | 🌐 Go | 📅 2026-07-07 - TUI for managing WireGuard configuration files.
* [gzip-size-cli](https://github.com/sindresorhus/gzip-size-cli) ⭐ 193 | 🐛 0 | 🌐 JavaScript | 📅 2021-11-23 - Get the gzipped size of a file.
* [deadlink](https://github.com/nschloe/deadlink) ⭐ 177 | 🐛 6 | 📅 2025-12-17 - Parses text files for HTTP URLs and checks if they are still valid. Good to use on Markdown documentation files.
* [JsonGenius](https://github.com/semanser/JsonGenius) ⭐ 177 | 🐛 1 | 🌐 Go | 📅 2023-10-11 - Self-hosted scraping API that extracts structured data described by a JSON Schema.
* [grc](https://github.com/pengwynn/grc) ⭐ 141 | 🐛 4 | 🌐 JavaScript | 📅 2015-09-02 - (Generic Colourizer) - parse a given text stream and to colorize it according to regexp written in configuration files; different patterns can be associated to file types.
* [logu](https://github.com/ynqa/logu) ⭐ 123 | 🐛 0 | 🌐 Rust | 📅 2025-07-11 - Extract patterns from (streaming) unstructured log messages.
* [HASHA CLI](https://github.com/sindresorhus/hasha-cli) ⭐ 82 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-12 - Hashing made simple. Get the hash of text or stdin.
* [Line Select](https://github.com/urbanogilson/lineselect) ⭐ 74 | 🐛 2 | 🌐 Rust | 📅 2026-03-31 - A powerful utility enabling interactive line selection from stdin, allowing to seamlessly integrate, pause, select, and refine your pipeline, enhancing data processing precision.
* [dir2txt](https://github.com/shubhamoy/dir2txt) ⭐ 70 | 🐛 5 | 🌐 C++ | 📅 2025-04-18 - A blazing-fast CLI tool to export a directory's structure and contents into a neatly formatted `.txt` or `.json` file.
* [Normalize Country](https://github.com/sshaw/normalize_country) ⭐ 70 | 🐛 2 | 🌐 Ruby | 📅 2025-02-22 - Convert country names and codes to a standard.
* [grits](https://github.com/solidiquis/grits) ⭐ 57 | 🐛 5 | 🌐 Rust | 📅 2025-01-21 - A simple line-text formatter that makes it simple to parse, filter, and format live logs turning noise into meaningful insights.
* [swordfish-rs](https://github.com/vim-zz/swordfish-rs) ⭐ 53 | 🐛 0 | 🌐 Rust | 📅 2023-06-11 - Mimics real person behavior with real-time typing into terminal uses a screenplay where text and timings are specified.
* [analiticcl](https://github.com/proycon/analiticcl) ⭐ 40 | 🐛 5 | 🌐 Rust | 📅 2026-02-10 - An approximate string matching or fuzzy-matching system for spelling correction, normalisation or post-OCR correction.
* [logshark](https://github.com/ugosan/logshark) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2022-12-13 - Logshark is a debugger CLI for JSON logs written in Go.
* [to-single-quotes](https://github.com/sindresorhus/to-single-quotes-cli) ⭐ 27 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-18 - Convert matching double-quotes to single-quotes.
* [modo](https://github.com/elliot40404/modo) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2025-01-22 - A cross platform cli app to interact with markdown style checkboxes within any text file.
* [detect-indent-cli](https://github.com/sindresorhus/detect-indent-cli) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-15 - Detect the indentation of code.
* [to-double-quotes](https://github.com/sindresorhus/to-double-quotes-cli) ⭐ 22 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-18 - Convert matching single-quotes to double-quotes.
* [squeeze](https://github.com/aymericbeaumet/squeeze) ⭐ 20 | 🐛 1 | 🌐 Rust | 📅 2026-08-11 - Enables to extract rich information from any text (raw, JSON, HTML, YAML, etc).
* [fullname-cli](https://github.com/sindresorhus/fullname-cli) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2024-03-12 - Get the fullname of the current user.
* [Output as Format](https://github.com/sshaw/output-as-format) ⭐ 15 | 🐛 0 | 🌐 Perl | 📅 2020-05-30 - Output stdin as GitHub/Slack/Jira etc... formatted code, lists, or quotes.
* [seaq](https://github.com/nt54hamnghi/seaq) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2026-02-08 - seaq (pronounced "seek") allows you to extract text data from the web and process it with your favorite prompt and LLM model, all from your terminal.
* [toc](https://github.com/AlphaJack/toc) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-01-24 - Generate a table of contents from the comments of a file.
* [hburger](https://github.com/niqodea/hburger) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2024-12-22 - Shorten long strings and paths while preserving readability.
* [lingua-cli](https://github.com/proycon/lingua-cli) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2024-10-12 - This is a small command-line tool for language detection, it is a simple wrapper around the lingua-rs library for Rust.
* [xcut](https://github.com/kyotalab/xcut) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2025-06-03 - A flexible field extractor and filter tool for the command line (extended version of the Unix cut command).
* [neospeller](https://github.com/richardhapb/neospeller) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2026-05-07 - Spell checking for different languages comments.
* [catdir](https://github.com/emilastanov/catdir) ⭐ 4 | 🐛 3 | 🌐 Python | 📅 2025-05-14 - A simple CLI utility that traverses directories and concatenates the contents of all files within a folder and its subfolders, similar to the Unix cat command, but for entire directory trees.
* [hyphertool](https://github.com/proycon/hyphertool/) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2025-02-21 - Command-line tool for syllabification and hyphenisation for multiple languages.
* [stam-tools](https://github.com/annotation/stam-tools) ⭐ 4 | 🐛 7 | 🌐 Rust | 📅 2026-08-13 - A collection of command-line tools for working with STAM, a data-model for stand-off annotations on text.
* [catselector](https://github.com/alexaldearroyo/catselector) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2025-08-09 - Interactive file selector for concatenating and exporting text files.
* [json-leaves](https://github.com/talwrii/json-leaves) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-04-30 - Extract the leaves from a JSON file and show the paths to said leaves.
* [charfreq](https://github.com/proycon/charfreq) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2024-07-07 - Very simple command-line tool that counts (unicode) character frequency from standard input.
* [cho](https://github.com/jaggzh/cho) ⭐ 2 | 🐛 0 | 🌐 Makefile | 📅 2026-05-22 - The safe echo & quoting utility you always knew you needed, but were too afraid to ask \[for].
* [lexmatch](https://github.com/proycon/lexmatch) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2024-07-03 - This is a simple lexicon matching tool that, given a lexicon of words or phrases, identifies all matches in a given target text, returning their exact positions. It can be used compute a frequency list for a lexicon, on a target corpus.
* [ssam](https://github.com/proycon/ssam) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2021-03-03 - Ssam, short for split sampler, splits one or more text-based input files into multiple sets using random sampling. This is useful for splitting data into a training, test and development sets.
* [Colibri Core](https://proycon.github.io/colibri-core/) - A software to quickly and efficiently count and extract patterns (n-grams and more) from large corpus data, to extract various statistics on the extracted patterns, and to compute relations between the extracted patterns.
* [skroll](https://z3bra.org/skroll/) - A small utility that you can use to make a text scroll. Pipe text to it, and it will scroll a given number of letters from right to left.
* [ucto](https://languagemachines.github.io/ucto/) - Ucto tokenizes text files: it separates words from punctuation, and splits sentences. It has rules (regular-expression based) for several languages.

## <a name="data-management"></a>Data management

Tools to manage data files.

* [sampler](https://github.com/sqshq/sampler) ⭐ 14,788 | 🐛 62 | 🌐 Go | 📅 2024-02-22 - Sampler is a tool for shell commands execution, visualization, and alerting. Configured with a simple YAML file.
* [ROAPI](https://github.com/roapi/roapi) ⭐ 3,418 | 🐛 66 | 🌐 Rust | 📅 2026-03-25 - ROAPI automatically spins up read-only APIs for static datasets without requiring you to write a single line of code.
* [IRedis](https://github.com/laixintao/iredis) ⭐ 2,740 | 🐛 50 | 🌐 Python | 📅 2026-07-27 - Interactive Redis: A CLI for Redis with autocompletion and Syntax Highlighting.
* [ttyplot](https://github.com/tenox7/ttyplot) ⭐ 1,375 | 🐛 11 | 🌐 C | 📅 2026-07-28 - A realtime plotting utility for terminals with data input from stdin/pipe.
* [kaskade](https://github.com/sauljabin/kaskade) ⭐ 1,023 | 🐛 15 | 🌐 Python | 📅 2026-03-02 - TUI for kafka, which allows you to interact and consume topics from your terminal in style.
* [ramda-cli](https://github.com/raine/ramda-cli) ⭐ 583 | 🐛 26 | 🌐 LiveScript | 📅 2022-12-30 - A tool for processing data with functional pipelines.
* [crudini](https://github.com/pixelb/crudini) ⭐ 490 | 🐛 16 | 🌐 Python | 📅 2025-06-03 - A utility for manipulating .ini files.
* [datadash](https://github.com/keithknott26/datadash) ⭐ 315 | 🐛 0 | 🌐 Go | 📅 2026-05-07 - Visualize and graph data in the terminal.
* [datasetGPT](https://github.com/radi-cho/datasetGPT) ⭐ 300 | 🐛 4 | 🌐 Python | 📅 2023-08-25 - A command-line interface and a Python library for inferencing Large Language Models to generate textual datasets.
* [lowcharts](https://github.com/juan-leon/lowcharts) ⭐ 250 | 🐛 10 | 🌐 Rust | 📅 2025-12-22 - lowcharts is meant to be used in those scenarios where we have numerical data in text files that we want to display in the terminal to do a basic analysis.
* [Redis Viewer](https://github.com/SaltFishPr/redis-viewer) ⭐ 152 | 🐛 6 | 🌐 Go | 📅 2026-07-04 - A tool to view Redis data in terminal.
* [osmf](https://github.com/codesoap/osmar) ⭐ 133 | 🐛 0 | 🌐 Go | 📅 2025-07-21 - OpenStreetMap find - A simple command line tool to explore OSM data.
* [redis\_tui](https://github.com/mat2cc/redis_tui) ⭐ 118 | 🐛 2 | 🌐 Go | 📅 2025-04-20 - Redis terminal browser application.
* [chndlr](https://github.com/bharatvaj/chndlr) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2025-02-21 - Replacement for xdg-open; It determines the appropriate application to open a file or URL based on user-defined rules in configuration.
* [dateutils](http://www.fresse.org/dateutils/) - Dateutils are a bunch of tools that revolve around fiddling with dates and times in the command line with a strong focus on use cases that arise when dealing with large amounts of financial data.
* [GNU Recutils](https://www.gnu.org/software/recutils/manual/) - Set of tools and libraries to access human-editable, text-based databases called recfiles.
* [gnuplot](https://www.explainshell.com/explain/1/gnuplot) - Generate two and three-dimensional plots of data.
* [zq](https://zed.brimdata.io/docs/commands/zq/) - A command-line tool that uses the Zed language for pipeline-style search and analytics. It can query a variety of data formats (CSV, JSON, etc.) in files, over HTTP, or in S3 storage.

## <a name="data-management-json"></a>Data management - JSON/YAML/etc.

Tools to manage data files, dedicated to JSON, YAML and other similar formats.

* [fx](https://github.com/antonmedv/fx) ⭐ 20,589 | 🐛 25 | 🌐 Go | 📅 2026-07-28 - Command-line JSON viewer.
* [yq](https://github.com/mikefarah/yq) ⭐ 15,871 | 🐛 287 | 🌐 Go | 📅 2026-08-20 - Portable command-line YAML processor.
* [gron](https://github.com/tomnomnom/gron) ⭐ 14,498 | 🐛 50 | 🌐 Go | 📅 2025-05-31 - gron transforms JSON into discrete assignments to make it easier to grep for what you want and see the absolute 'path' to it.
* [jc](https://github.com/kellyjonbrazil/jc) ⭐ 8,666 | 🐛 47 | 🌐 Python | 📅 2026-08-25 - Serializes the output of command line tools to JSON.
* [dasel](https://github.com/TomWright/dasel) ⭐ 8,025 | 🐛 25 | 🌐 Go | 📅 2026-08-16 - Allows you to query and modify data structures using selector strings.
* [jid](https://github.com/simeji/jid) ⭐ 7,136 | 🐛 10 | 🌐 Go | 📅 2026-08-02 - You can drill down JSON interactively by using filtering queries like jq.
* [jnv](https://github.com/ynqa/jnv) ⭐ 6,093 | 🐛 30 | 🌐 Rust | 📅 2026-08-20 - Interactive JSON filter using jq.
* [jo](https://github.com/jpmens/jo) ⭐ 4,862 | 🐛 7 | 🌐 C | 📅 2025-06-20 - A small utility to create JSON objects from the command line.
* [gojq](https://github.com/itchyny/gojq) ⭐ 3,796 | 🐛 18 | 🌐 Go | 📅 2026-08-23 - Pure Go implementation of jq.
* [jaq](https://github.com/01mf02/jaq) ⭐ 3,725 | 🐛 22 | 🌐 Rust | 📅 2026-08-19 - jaq is a clone of the JSON data processing tool jq, that aims to support a large subset of jq's syntax and operations.
* [jqp](https://github.com/noahgorstein/jqp) ⭐ 2,828 | 🐛 24 | 🌐 Go | 📅 2026-02-06 - A TUI playground for exploring jq.
* [Graphtage](https://github.com/trailofbits/graphtage) ⭐ 2,478 | 🐛 29 | 🌐 Python | 📅 2026-08-04 - Graphtage is a command-line utility and underlying library for semantically comparing and merging tree-like structures, such as JSON, XML, HTML, YAML, plist, and CSS files.
* [rq](https://github.com/dflemstr/rq) ⭐ 2,299 | 🐛 39 | 🌐 Rust | 📅 2023-12-21 - Record Query - A tool for doing record analysis and transformation.
* [jj](https://github.com/tidwall/jj) ⭐ 2,062 | 🐛 19 | 🌐 Go | 📅 2023-12-16 - A command line utility that provides a fast and simple way to retrieve or update values from JSON documents.
* [JSON.sh](https://github.com/dominictarr/JSON.sh) ⭐ 2,029 | 🐛 19 | 🌐 Shell | 📅 2020-12-15 - A JSON parser written in shell, compatible with ash, bash, dash and zsh.
* [underscore-cli](https://github.com/ddopson/underscore-cli) ⭐ 1,733 | 🐛 34 | 🌐 JavaScript | 📅 2020-11-02 - Command-line utility-belt for hacking JSON and JavaScript.
* [json](https://github.com/trentm/json) ⭐ 1,562 | 🐛 50 | 🌐 JavaScript | 📅 2024-01-23 - A "json" command for massaging JSON on your Unix command line.
* [Jsawk](https://github.com/micha/jsawk) ⭐ 1,385 | 🐛 28 | 🌐 Shell | 📅 2021-08-31 - Like awk, but for JSON. You work with an array of JSON objects read from stdin, filter them using JavaScript to produce a results array that is printed to stdout.
* [jp](https://github.com/jmespath/jp) ⭐ 787 | 🐛 20 | 🌐 Python | 📅 2023-06-15 - A command line interface to JMESPath, an expression language for manipulating JSON.
* [TickTick](https://github.com/kristopolous/TickTick) ⭐ 584 | 🐛 12 | 🌐 Shell | 📅 2020-05-29 - TickTick enables you to put JSON in bash scripts. Yes, just encapsulate them with two back-ticks.
* [jello](https://github.com/kellyjonbrazil/jello) ⭐ 531 | 🐛 7 | 🌐 Python | 📅 2025-05-30 - CLI tool to filter JSON and JSON Lines data with Python syntax, similar to - surprise :-), jq!
* [jtc](https://github.com/ldn-softdev/jtc) ⭐ 507 | 🐛 11 | 🌐 C++ | 📅 2022-10-29 - JSON manipulation and transformation.
* [jl](https://github.com/chrisdone/jl) ⚠️ Archived - jl ("JSON lambda") is a tiny functional language for querying and manipulating JSON.
* [faq](https://github.com/jzelinskie/faq) ⭐ 464 | 🐛 20 | 🌐 Go | 📅 2024-10-02 - Format Agnostic jQ - process various formats with libjq.
* [JSON.awk](https://github.com/step-/JSON.awk) ⭐ 450 | 🐛 1 | 🌐 Awk | 📅 2022-08-21 - A practical JSON parser written in awk.
* [jshon](https://github.com/keenerd/jshon) ⭐ 391 | 🐛 27 | 🌐 C | 📅 2023-08-06 - Jshon is a JSON parser designed for maximum convenience within the shell.
* [jqview](https://github.com/fiatjaf/jqview) ⭐ 369 | 🐛 1 | 🌐 Go | 📅 2020-06-30 - Simplest possible native GUI for inspecting JSON.
* [jtbl](https://github.com/kellyjonbrazil/jtbl) ⭐ 343 | 🐛 2 | 🌐 Python | 📅 2024-04-02 - A simple CLI tool to print JSON and JSON Lines data as a table in the terminal.
* [jsonpp](https://github.com/jmhodges/jsonpp) ⭐ 334 | 🐛 5 | 🌐 Go | 📅 2022-07-14 - A fast command line JSON pretty printer.
* [RecordStream](https://github.com/benbernard/RecordStream) ⭐ 307 | 🐛 6 | 🌐 Perl | 📅 2026-05-28 - Command-line tools for slicing and dicing JSON records.
* [GROQ](https://github.com/sanity-io/groq-cli) ⭐ 236 | 🐛 14 | 🌐 JavaScript | 📅 2026-08-07 - The CLI tool consumes both JSON and NDJSON documents. You can pass in data from a local file, or from piping to standard input.
* [jsonv.sh](https://github.com/archan937/jsonv.sh) ⭐ 221 | 🐛 9 | 🌐 Awk | 📅 2016-11-19 - A Bash command line tool for converting JSON to CSV.
* [JSON Command](https://github.com/zpoley/json-command) ⭐ 164 | 🐛 2 | 🌐 JavaScript | 📅 2015-11-23 - JSON command line processing toolkit: no more writing code to inspect or transform JSON objects.
* [YAML Paths](https://github.com/wwkimball/yamlpath) ⭐ 138 | 🐛 0 | 🌐 Python | 📅 2026-05-02 - YAML/JSON/EYAML/Compatible get/set/merge/validate/scan/convert/diff processors using powerful, intuitive, command-line friendly syntax.
* [jellex](https://github.com/kellyjonbrazil/jellex) ⭐ 120 | 🐛 4 | 🌐 Python | 📅 2023-10-24 - TUI to filter JSON and JSON Lines data with Python syntax.
* [vj](https://github.com/busyloop/vj) ⭐ 98 | 🐛 2 | 🌐 Ruby | 📅 2018-01-02 - JSON Humanizer makes JSON human-readable by applying visual formatting.
* [JSON-Grep](https://github.com/ploubser/JSON-Grep) ⭐ 94 | 🐛 7 | 🌐 Ruby | 📅 2024-08-05 - JGrep is a command line tool and API for parsing JSON documents based on logical expressions.
* [jsed](https://github.com/jtopjian/jsed) ⭐ 62 | 🐛 1 | 🌐 Go | 📅 2020-08-21 - jsed is a small command-line utility to add, remove, and search for data in a JSON structure.
* [jp](https://github.com/therealklanni/jp) ⭐ 53 | 🐛 0 | 🌐 JavaScript | 📅 2019-02-14 - A tiny command-line tool for parsing JSON from any source.
* [jf](https://github.com/sayanarijit/jf) ⭐ 43 | 🐛 0 | 🌐 Rust | 📅 2026-05-18 - A small utility to safely format and print JSON objects in the commandline.
* [jsongrep](https://github.com/dsc/jsongrep) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2020-07-20 - A shell tool to search and select bits out of JSON documents.
* [Frontmatter CLI Tool](https://github.com/marad/frontmatter) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2025-11-14 - CLI tool for managing YAML frontmatter in text files; Built with Go and optimized for performance with large files.
* [Konfigo](https://github.com/ebogdum/konfigo) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2026-08-17 - Command-line tool designed to work with multiple configuration file formats like JSON, YAML, TOML.
* [jayin](https://github.com/we-cli/jayin) ⭐ 14 | 🐛 1 | 🌐 JavaScript | 📅 2024-11-07 - Piping with js at terminal.
* [jsongrep](https://github.com/terrycojones/jsongrep) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2015-03-09 - Python for extracting pieces of JSON objects
* [jless](https://pauljuliusmartinez.github.io/) - Command-line JSON viewer designed for reading, exploring, and searching through JSON data.
* [jq](https://stedolan.github.io/jq/) - (JSON Query?) - sed-like processor for JSON data; can be used to process JSON files and data streams and perform operations such as those allowed by `cat`, `sed`, `grep` and `awk` on regular text files.

## <a name="data-management-tabular"></a>Data management - Tabular data

Tools to manage tabular data files, such as CSV, spreadsheets, and database tables.

* [Dolt](https://github.com/dolthub/dolt) ⭐ 24,265 | 🐛 709 | 🌐 Go | 📅 2026-08-24 - Dolt is Git for Data! Dolt is a SQL database that you can fork, clone, branch, merge, push and pull just like a git repository.
* [pgcli](https://github.com/dbcli/pgcli) ⭐ 13,366 | 🐛 41 | 🌐 Python | 📅 2026-08-24 - Postgres CLI with autocompletion and syntax highlighting.
* [mycli](https://github.com/dbcli/mycli) ⭐ 11,967 | 🐛 3 | 🌐 Python | 📅 2026-08-24 - A command line client for MySQL that can do autocompletion and syntax highlighting.
* [usql](https://github.com/xo/usql) ⭐ 10,087 | 🐛 118 | 🌐 Go | 📅 2026-06-19 - Universal command-line interface for PostgreSQL, MySQL, Oracle Database, SQLite3, Microsoft SQL Server, and others, including NoSQL and non-relational databases.
* [Miller](https://github.com/johnkerl/miller) ⭐ 10,002 | 🐛 71 | 🌐 Go | 📅 2026-08-24 - Miller is like awk, sed, cut, join, and sort for data formats such as CSV, TSV, JSON, JSON Lines, and positionally-indexed.
* [textql](https://github.com/dinedal/textql) ⭐ 9,106 | 🐛 38 | 🌐 Go | 📅 2023-10-22 - Execute SQL against structured text like CSV or TSV.
* [csvkit](https://github.com/wireservice/csvkit) ⭐ 6,409 | 🐛 40 | 🌐 Python | 📅 2026-08-03 - A suite of command-line tools for converting to and working with CSV, the king of tabular file formats.
* [harlequin](https://github.com/tconbeer/harlequin) ⭐ 6,345 | 🐛 44 | 🌐 Python | 📅 2026-08-24 - The SQL IDE for Your Terminal.
* [rainfrog](https://github.com/achristmascarl/rainfrog) ⭐ 5,289 | 🐛 14 | 🌐 Rust | 📅 2026-08-25 - A database management tui for PostGres.
* [LAZYSQL](https://github.com/jorgerojas26/lazysql) ⭐ 4,238 | 🐛 47 | 🌐 Go | 📅 2026-08-22 - A cross-platform TUI database management tool written in Go.
* [csvlens](https://github.com/YS-L/csvlens) ⭐ 3,939 | 🐛 59 | 🌐 Rust | 📅 2026-07-04 - CSV file viewer; like `less` but made for CSV.
* [qsv](https://github.com/jqnatividad/qsv) ⭐ 3,766 | 🐛 29 | 🌐 Rust | 📅 2026-08-24 - CSVs sliced, diced & analyzed.
* [qsv](https://github.com/dathere/qsv) ⭐ 3,766 | 🐛 29 | 🌐 Rust | 📅 2026-08-24 - qsv is a command line program for querying, slicing, indexing, analyzing, filtering, enriching, transforming, sorting, validating, joining, formatting & converting tabular data (CSV, spreadsheets, DBs, parquet, etc).
* [gobang](https://github.com/TaKO8Ki/gobang) ⭐ 3,317 | 🐛 57 | 🌐 Rust | 📅 2023-11-10 - A cross-platform TUI database management tool written in Rust.
* [litecli](https://github.com/dbcli/litecli) ⭐ 3,293 | 🐛 46 | 🌐 Python | 📅 2026-06-18 - CLI for SQLite Databases with autocompletion and syntax highlighting.
* [dblab](https://github.com/danvergara/dblab) ⭐ 3,189 | 🐛 15 | 🌐 Go | 📅 2026-08-18 - Interactive client for PostgreSQL, MySQL, SQLite3, Oracle and SQL Server.
* [tabiew](https://github.com/shshemi/tabiew) ⭐ 3,084 | 🐛 16 | 🌐 Rust | 📅 2026-08-17 - A lightweight, terminal-based application to view and query delimiter separated value formatted documents, such as CSV or TSV files.
* [sq](https://github.com/neilotoole/sq) ⭐ 2,554 | 🐛 68 | 🌐 Go | 📅 2026-08-24 - Command line tool that provides jq-style access to structured data sources such as SQL databases, or document formats like CSV or Excel.
* [TV](https://github.com/alexhallam/tv) ⭐ 2,165 | 🐛 28 | 🌐 Rust | 📅 2025-08-21 - Cross-platform CSV pretty printer made to maximize viewer enjoyment.
* [sqlite-utils](https://github.com/simonw/sqlite-utils) ⭐ 2,156 | 🐛 106 | 🌐 Python | 📅 2026-08-14 - Python CLI utility and library for manipulating SQLite databases.
* [termdbms](https://github.com/mathaou/termdbms) ⭐ 1,820 | 🐛 6 | 🌐 Go | 📅 2022-06-11 - A TUI for viewing and editing databases, written in pure Go.
* [Soul](https://github.com/thevahidal/soul) ⭐ 1,682 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-10 - A SQLite REST and real-time server.
* [csvq](https://github.com/mithrandie/csvq) ⭐ 1,627 | 🐛 27 | 🌐 Go | 📅 2024-07-25 - SQL-like query language for CSV.
* [TSV Utilities](https://github.com/eBay/tsv-utils) ⭐ 1,482 | 🐛 24 | 🌐 D | 📅 2022-09-14 - Command line tools for large, tabular data files.
* [dolphie](https://github.com/charles-001/dolphie) ⭐ 1,193 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - Your single pane of glass (TUI) for real-time analytics into MySQL/MariaDB & ProxySQL.
* [daff](https://github.com/paulfitz/daff) ⭐ 922 | 🐛 47 | 🌐 Java | 📅 2026-05-27 - Efficient table comparison and alignment, supporting formats like CSV and SQLite, useful for data analysis and synchronization tasks.
* [tabview](https://github.com/TabViewer/tabview) ⭐ 474 | 🐛 34 | 🌐 Python | 📅 2022-12-22 - Python curses command line CSV and tabular data viewer.
* [zsv](https://github.com/liquidaty/zsv) ⭐ 396 | 🐛 25 | 🌐 C | 📅 2026-08-23 - The world's fastest (simd) CSV parser, with an extensible, multi-purpose CLI.
* [DBee](https://github.com/murat-cileli/dbee) ⭐ 171 | 🐛 3 | 🌐 Go | 📅 2024-06-22 - Fast & Minimalistic Database Browser (MySQL, MariaDB, PostgreSQL).
* [levite](https://github.com/RauliL/levite) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2026-05-09 - A TUI spreadsheet application that uses an RPN formulas and features a Vi-friendly interface.
* [YAS-QWIN](https://github.com/sebastiancarlos/yas-qwin) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-03-06 - YAS-QWIN (Yet Another SQL-Query Writing Interface) is a CLI tool for building (and optionally running) SQL queries.
* [csvsuite](https://github.com/wiluite/csvsuite) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2025-12-12 - A suite of tools to process CSV files, written in C++.
* [csvtk](https://bioinf.shenwei.me/csvtk/) - A cross-platform, efficient and practical CSV/TSV toolkit written in Go.
* [q](http://harelba.github.io/q/) - Execute SQL-like queries on CSVs/TSVs tabular data files; each tabular file is treated as a database table; supports all SQL constructs (`WHERE`, `GROUP BY`, `JOIN`).
* [VisiData](https://www.visidata.org/) - Interactive multitool for tabular data. It combines the clarity of a spreadsheet, the efficiency of the terminal, and the power of Python, into a lightweight utility which can handle millions of rows with ease.
* [xsv](https://www.johndcook.com/blog/2019/12/31/sql-join-csv-files/) - Doing a SQL join with CSV files.

## <a name="option-picker"></a>Fuzzy finders and option pickers

Fuzzy finders and generic option pickers in lists of strings.

* [fzf](https://github.com/junegunn/fzf) ⭐ 82,638 | 🐛 327 | 🌐 Go | 📅 2026-08-24 - (FuZzy Finder) - a general-purpose command-line finder with fuzzy search/filter capabilities, good integration with `vim`.
* [skim](https://github.com/lotabout/skim) ⭐ 6,934 | 🐛 4 | 🌐 Rust | 📅 2026-08-22 - Fuzzy Finder in rust.
* [television](https://github.com/alexpasmantier/television) ⭐ 6,206 | 🐛 82 | 🌐 Rust | 📅 2026-08-16 - Blazing fast general purpose fuzzy finder TUI.
* [percol](https://github.com/mooz/percol) ⭐ 3,326 | 🐛 51 | 🌐 Python | 📅 2023-12-30 - A Python script that "1) receives input lines from `stdin` or a file, 2) lists the input lines and waits for input that filter/select the line(s), 3) outputs the selected line(s) to `stdout`"; can be used to add interactivity to many regular shell commands.
* [fzy](https://github.com/jhawthorn/fzy) ⭐ 3,297 | 🐛 57 | 🌐 C | 📅 2025-07-29 - Better fuzzy finder.
* [smenu](https://github.com/p-gen/smenu) ⭐ 2,492 | 🐛 4 | 🌐 C | 📅 2026-04-17 - Started as a lightweight and flexible terminal menu generator, it evolved into a powerful and versatile CLI selection tool for interactive or scripting use.
* [pick](https://github.com/mptre/pick) ⭐ 841 | 🐛 10 | 🌐 C | 📅 2023-05-17 - Choose one option from a set of choices using an interface with fuzzy search functionality.
* [pmenu](https://github.com/sgtpep/pmenu) ⭐ 132 | 🐛 4 | 🌐 Python | 📅 2022-03-29 - A dynamic terminal-based menu inspired by dmenu.
* [luneta](https://github.com/fbeline/luneta) ⚠️ Archived - Interactive filter that can be easily composed within any script.
* [tp](https://github.com/minefuto/tp) ⭐ 59 | 🐛 0 | 🌐 Go | 📅 2026-05-29 - Display the result of the commands at every keystroke.
* [Fnf](https://github.com/leo-arch/fnf) ⭐ 51 | 🐛 3 | 🌐 C | 📅 2026-04-04 - An interactive fuzzy finder for the terminal; As you type a query, fnf  filters candidates and instantly updates the sorted list.
* [tui-datepicker](https://github.com/maraloon/pickdate) ⭐ 46 | 🐛 4 | 🌐 Go | 📅 2025-10-27 - Select date in terminal with vim-motions and copy to buffer.
* [shmenu](https://github.com/duclos-cavalcanti/shmenu) ⭐ 31 | 🐛 0 | 🌐 Shell | 📅 2023-02-17 - Menu TUI tool written solely in bash.
* [fss](https://github.com/5n00py/fss) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2023-12-08 - User-friendly command-line search scripts combining find and grep utilities with fzf previewing and direct actions on specific file types.
* [choose](https://github.com/jagprog5/choose) ⭐ 9 | 🐛 0 | 🌐 C++ | 📅 2024-12-05 - NCurses based token selector with a nice terminal user interface for selecting tokens. Selecting a line from the bash history is only one of its use cases.
* [fuzzysh](https://github.com/yazgoo/fuzzysh) ⭐ 9 | 🐛 0 | 🌐 Ruby | 📅 2024-12-18 - Minimalist selector in shell, inspired by fzf.
* [cmenu](https://github.com/10xJSChad/cmenu) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2024-07-30 - Vaguely dmenu-like minimal TUI menu utility, it reads entries from stdin, creates a selection menu, and writes the selected entry to stdout.
* [lSel](https://github.com/unsigned-enby/lSel) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2024-11-19 - Simple no-fuss TUI selection menu for use in scripts.

## <a name="markdown"></a>Markdown

Utilities to display, convert and reformat Markdown files.

* [glow](https://github.com/charmbracelet/glow) ⭐ 27,025 | 🐛 222 | 🌐 Go | 📅 2026-08-16 - TUI that renders Markdown files, with keybindings similar to `less` and support for styles and cloud encrypted storing
* [mdBook](https://github.com/rust-lang/mdBook) ⭐ 22,095 | 🐛 676 | 🌐 Rust | 📅 2026-08-22 - Create book from Markdown files.
* [Grip](https://github.com/joeyespo/grip) ⭐ 6,823 | 🐛 125 | 🌐 Python | 📅 2024-07-10 - GitHub Readme Instant Preview - Preview Markdown files as GitHub would render them.
* [DocToc](https://github.com/thlorenz/doctoc) ⭐ 4,460 | 🐛 27 | 🌐 JavaScript | 📅 2026-08-04 - Generates table of contents for Markdown files inside local git repository. Links are compatible with anchors generated by GitHub or other sites.
* [Frogmouth](https://github.com/Textualize/frogmouth) ⭐ 3,271 | 🐛 46 | 🌐 Python | 📅 2024-08-01 - A Markdown viewer / browser for the terminal.
* [Terminal Markdown Viewer](https://github.com/axiros/terminal_markdown_viewer) ⭐ 1,884 | 🐛 41 | 🌐 Python | 📅 2024-05-15 - Python based Markdown viewer with themes source code highlighting and a directory change monitor.
* [mdformat](https://github.com/executablebooks/mdformat) ⭐ 812 | 🐛 58 | 🌐 Python | 📅 2026-08-17 - Mdformat is an opinionated Markdown formatter that can be used to enforce a consistent style in Markdown files.
* [mdt](https://github.com/robolab-pavia/mdt) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-05-11 - MarkDown in the Terminal. A Markdown viewer with themes defined by JSON files and interactive mode to open links and word-wrapping adaptable to the terminal width.
* [lowdown](https://kristaps.bsd.lv/lowdown/) - Markdown translator (HTML5, roff, LaTeX, gemini, OpenDocument, and terminal output)

# <a name="Development-and-Programming"></a>Development and Programming

## <a name="editors"></a>Editors

Text editors.

* [micro](https://github.com/zyedidia/micro) ⭐ 29,433 | 🐛 1,038 | 🌐 Go | 📅 2026-08-25 - Aims to be a successor to [`nano`](https://www.nano-editor.org/). Aiming to be easy to use, it has a nano-like keybindings menu; also takes advantage of the full capabilities of modern terminals, supports mutiple cursors, and has a plugin system. Written in Go.
* [edit](https://github.com/microsoft/edit) ⭐ 14,485 | 🐛 172 | 🌐 Rust | 📅 2026-08-23 - This editor pays homage to the classic MS-DOS Editor, but with a modern interface and input controls similar to VS Code.
* [slap](https://github.com/slap-editor/slap) ⭐ 6,189 | 🐛 115 | 🌐 JavaScript | 📅 2021-11-01 - Text editor inspired by [Sublime Text](https://www.sublimetext.com/) written in NodeJS, extendable in JavaScript.
* [vis](https://github.com/martanne/vis) ⭐ 4,695 | 🐛 147 | 🌐 C | 📅 2026-08-20 - "a modern, legacy free, simple yet efficient vim-like editor", and more: "The intention is not to be bug for bug compatible with vim, instead a similar editing experience should be provided. The goal could thus be summarized as 80% of vim's features implemented in roughly 1% of the code"; the editor is scriptable in LUA and supports editing large files.
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,123 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.
* [ox](https://github.com/curlpipe/ox) ⭐ 3,733 | 🐛 33 | 🌐 Rust | 📅 2026-04-23 - An independent Rust text editor.
* [zee](https://github.com/zee-editor/zee) ⭐ 1,799 | 🐛 44 | 🌐 Rust | 📅 2025-02-06 - Zee is a modern editor for the terminal, in the spirit of Emacs. It is written in Rust and it is somewhat experimental.
* [vy](https://github.com/vyapp/vy) ⚠️ Archived - A vim-like in Python made from scratch.
* [o](https://github.com/xyproto/orbiton) ⭐ 697 | 🐛 1 | 🌐 Go | 📅 2026-08-21 - Configuration-free text editor and IDE limited to VT100. Suitable for writing git commit messages, editing Markdown, config files, source code, viewing man pages and for quick edit-compile cycles when programming.
* [Turbo](https://github.com/magiblot/turbo) ⭐ 675 | 🐛 37 | 🌐 C++ | 📅 2026-08-14 - An experimental text editor for the terminal, based on Scintilla and Turbo Vision.
* [C-EDIT](https://github.com/velorek1/c-edit) ⭐ 301 | 🐛 4 | 🌐 C | 📅 2026-01-29 - A text editor in C with drop down menus in the style of MS-DOS Editor.
* [aretext](https://github.com/aretext/aretext) ⭐ 285 | 🐛 6 | 🌐 Go | 📅 2026-08-24 - Minimalist text editor with vim-compatible key bindings.
* [vai](https://github.com/stefanoborini/vai) ⭐ 246 | 🐛 65 | 🌐 Python | 📅 2021-08-12 - Text editor similar to `vim` written in Python; many features are nicely replicated, some are still missing; however, the advantage of this implementation is its simplicity, maintainability and extensibility, thanks to the Python implementation.
* [Erys](https://github.com/natibek/erys) ⭐ 149 | 🐛 1 | 🌐 Python | 📅 2026-05-21 - Terminal Interface for Jupyter Notebooks.
* [Diakonos](https://github.com/Pistos/diakonos) ⭐ 140 | 🐛 24 | 🌐 Ruby | 📅 2026-06-13 - A powerful editor with “standard" keybindings and several advanced features; written in Ruby.
* [ash](https://github.com/akashnag/ash) ⭐ 127 | 🐛 4 | 🌐 Python | 📅 2023-10-10 - A simple and clean terminal-based text editor, that aims to be easy to use with modern key-bindings.
* [eon](https://github.com/tomas/eon) ⭐ 49 | 🐛 1 | 🌐 C | 📅 2021-01-06 - A light, modern editor for your terminal that doesn't want to be vim.
* [vicut](https://github.com/km-clay/vicut) ⭐ 45 | 🐛 0 | 🌐 Rust | 📅 2025-07-05 - Vim-based, scriptable and headless text editor for the command line, it can be used to extract fields, edit text files in-place and apply global substitutions and more.
* [ed](https://www.gnu.org/software/ed/) - GNU ed is a line-oriented text editor. It is used to create, display, modify and otherwise manipulate text files, both interactively and via shell scripts.
* [Emacs](https://www.gnu.org/software/emacs/) - One of the oldest text editors, free long-standing software project, with a huge amount of functionalities and extensions; implemented and extendable with E-Lisp.
* [Feather](https://www.feathereditor.com/) - The only terminal based text editor designed to work with BIG files.
* [Helix](https://helix-editor.com/) - A Kakoune / Neovim inspired editor, written in Rust. The editing model is very heavily based on Kakoune. It ships multiple selections, tree-sitter integration, powerful code manipulation, language server support and other modern builtin features.
* [jed](http://www.jedsoft.org/jed/index.html) - A text editor with a drop-down menu facility that make it especially user-friendly.
* [joe](http://joe-editor.sourceforge.net/) - (Joe's Own Editor) - a compact text editor written in C, a detailed list of features and missing ones is explicitly reported on the website. This editor is mentioned in several web sources for its capability in handling large files.
* [Kakoune](http://kakoune.org/) - Modal editor, faster as in less keystrokes, multiple selections, orthogonal design.
* [maki](https://sr.ht/~bscit/maki/) - A simple text editor with file navigation and an emphasis on preserving battery life.
* [nano](https://www.nano-editor.org/) - Easy to use, lightweight text editor; no complex keybindings to remember; the main ones are shown in the main menu.
* [neovim](https://neovim.io/) - A work in progress attempt to improve [vim](http://www.vim.org/), dropping older/unused OS compatibility, improving the codebase readability, modularity, and maintainability; it has chances to become the next choice of vim users.
* [Tilde](https://os.ghalkes.nl/tilde/) - Tilde is a text editor that provides an intuitive interface for people accustomed to GUI environments, usual shortcuts for common operation, a traditional menu bar, etc.
* [VE](http://www.inverary.net/ve/ve.html) - Lean, fast and feature rich text editor.
* [vim](http://www.vim.org/) - Historically one of the preferred text editors, behavior based on editing modes, plenty of plugins and tips to address every possible editing problem.
* [WordGrinder](https://cowlark.com/wordgrinder/) - From the website: "WordGrinder is a word processor for processing words. It is not WYSIWYG. It is not point and click. It is not a desktop publisher. It is not a text editor. It does not do fonts and it barely does styles. What it does do is words. It's designed for writing text. It gets out of your way and lets you type."

## <a name="git"></a>Git and accessories

Tools to support and extend the functionalities of the `git` version tracker.

* [Lazygit](https://github.com/jesseduffield/lazygit) ⭐ 81,603 | 🐛 1,025 | 🌐 Go | 📅 2026-08-21 - A simple terminal UI for git commands that simplify the execution of many operations making them interactive.
* [gitleaks](https://github.com/gitleaks/gitleaks) ⭐ 28,941 | 🐛 460 | 🌐 Go | 📅 2026-08-19 - Tool for detecting and preventing hardcoded secrets like passwords, api keys, and tokens in git repos.
* [GitUI](https://github.com/extrawurst/gitui) ⭐ 22,429 | 🐛 342 | 🌐 Rust | 📅 2026-08-04 - The comfort of a git GUI but right in your terminal, with keyboard only control, scalable UI, and features all the necessary operations of git.
* [git-extras](https://github.com/tj/git-extras) ⭐ 18,097 | 🐛 98 | 🌐 Shell | 📅 2026-08-17 - Little git extras like git-ignore, git-setup, git-changelog, git-release, git-effort and more.
* [tig](https://github.com/jonas/tig) ⭐ 13,318 | 🐛 231 | 🌐 C | 📅 2026-07-27 - An ncurses-based text-mode interface for `git` that can act as a repository browser, but can also assist in staging changes for commit at chunk level.
* [gh-dash](https://github.com/dlvhdr/gh-dash) ⭐ 12,387 | 🐛 98 | 🌐 Go | 📅 2026-08-01 - A beautiful CLI dashboard for GitHub.
* [BFG Repo-Cleaner](https://github.com/rtyley/bfg-repo-cleaner) ⭐ 12,173 | 🐛 275 | 🌐 Scala | 📅 2025-01-19 - Removes large or troublesome blobs like git-filter-branch does, but faster.
* [git-cliff](https://github.com/orhun/git-cliff) ⭐ 12,158 | 🐛 120 | 🌐 Rust | 📅 2026-08-22 - A highly customizable Changelog Generator that follows Conventional Commit specifications.
* [onefetch](https://github.com/o2sh/onefetch) ⭐ 12,031 | 🐛 65 | 🌐 Rust | 📅 2026-08-24 - Git repository summary on your terminal.
* [git-bug](https://github.com/MichaelMure/git-bug) ⭐ 10,015 | 🐛 176 | 🌐 Go | 📅 2026-07-06 - Distributed, offline-first bug tracker embedded in git, with bridges.
* [Soft Serve](https://github.com/charmbracelet/soft-serve) ⭐ 7,198 | 🐛 78 | 🌐 Go | 📅 2026-08-12 - Self-hostable Git server for the command line. One distinguished feature is the possibility to create new repositories with a push.
* [git-quick-stats](https://github.com/arzzen/git-quick-stats) ⭐ 7,001 | 🐛 3 | 🌐 Shell | 📅 2026-04-18 - A simple and efficient way to access various statistics in a git repository.
* [git-stats](https://github.com/IonicaBizau/git-stats) ⭐ 6,603 | 🐛 5 | 🌐 HTML | 📅 2025-11-09 - Local git statistics including GitHub-like contributions calendars.
* [git absorb](https://github.com/tummychow/git-absorb) ⭐ 5,697 | 🐛 28 | 🌐 Rust | 📅 2026-02-14 - git commit --fixup, but automatic.
* [forgit](https://github.com/wfxr/forgit) ⭐ 5,070 | 🐛 14 | 🌐 Shell | 📅 2026-08-21 - A utility tool powered by fzf for using git interactively.
* [grv](https://github.com/rgburke/grv) ⭐ 4,092 | 🐛 31 | 🌐 Go | 📅 2019-05-01 - Git Repository Viewer - A terminal based interface for viewing Git repositories. It allows refs, commits, and diffs to be viewed, searched and filtered.
* [git-secret](https://github.com/sobolevn/git-secret) ⭐ 4,038 | 🐛 152 | 🌐 Shell | 📅 2026-08-24 - A bash tool which stores private data inside a git repo; it uses users' public keys, allowing trusted users to access encrypted data using PGP and their secret keys.
* [mergestat-lite](https://github.com/mergestat/mergestat-lite) ⭐ 3,518 | 🐛 46 | 🌐 Go | 📅 2026-08-20 - A command-line tool for running SQL queries on git repositories and related data sources.
* [WRKFLW](https://github.com/bahdotsh/wrkflw) ⭐ 3,303 | 🐛 11 | 🌐 Rust | 📅 2026-07-03 - Command-line tool for validating and executing GitHub actions workflows locally, without a full GitHub environment.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) ⭐ 2,434 | 🐛 2 | 🌐 Shell | 📅 2026-06-19 - Interactive `git` with the help of `fzf`.
* [git-recall](https://github.com/Fakerr/git-recall) ⭐ 2,112 | 🐛 7 | 🌐 Shell | 📅 2021-04-22 - A simple tool that allows you to easily go through your commits and check what you or other contributors in your team did.
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,044 | 🐛 28 | 🌐 Rust | 📅 2026-05-11 - CLI search and replace. Show you a nice diff of proposed changes before you commit them.
* [gita](https://github.com/nosarthur/gita) ⭐ 1,925 | 🐛 36 | 🌐 Python | 📅 2026-07-06 - A command-line tool to manage multiple git repositories.
* [git-cz](https://github.com/streamich/git-cz) ⭐ 1,877 | 🐛 86 | 🌐 JavaScript | 📅 2025-09-10 - Semantic Git commits.
* [czg](https://github.com/Zhengqbbb/cz-git) ⭐ 1,520 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-22 - Interactively generate standardized commit messages.
* [fzf-git.sh](https://github.com/junegunn/fzf-git.sh) ⭐ 1,176 | 🐛 13 | 🌐 Shell | 📅 2026-08-06 - bash and zsh key bindings for Git objects, powered by fzf.
* [git commander](https://github.com/golbin/git-commander) ⭐ 1,121 | 🐛 19 | 🌐 JavaScript | 📅 2015-08-13 - A git tool with an easy interactive terminal interface.
* [dunk](https://github.com/darrenburns/dunk) ⭐ 888 | 🐛 22 | 🌐 Python | 📅 2025-04-19 - Prettier git diffs in the terminal.
* [git-peek](https://github.com/Jarred-Sumner/git-peek) ⭐ 756 | 🐛 3 | 🌐 JavaScript | 📅 2021-02-20 - git peek is the fastest way to open a remote git repository in your local text editor.
* [Froggit](https://github.com/thewizardshell/froggit) ⭐ 482 | 🐛 3 | 🌐 Go | 📅 2026-03-20 - Minimalist Git TUI with GitHub CLI integration.
* [gh-s](https://github.com/gennaro-tedesco/gh-s) ⭐ 412 | 🐛 1 | 🌐 Go | 📅 2025-08-20 - Search GitHub repositories interactively.
* [gh-f](https://github.com/gennaro-tedesco/gh-f) ⭐ 389 | 🐛 0 | 🌐 Shell | 📅 2025-09-23 - The ultimate, compact and snappy fzf extension for gh CLI.
* [ggc](https://github.com/bmf-san/ggc) ⭐ 284 | 🐛 2 | 🌐 Go | 📅 2026-08-24 - A modern Git CLI tool with both traditional command-line and interactive incremental-search UI.
* [gitlab-cli](https://github.com/vishwanatharondekar/gitlab-cli) ⭐ 266 | 🐛 5 | 🌐 JavaScript | 📅 2024-01-19 - Create GitLab merge requests.
* [gitnr](https://github.com/reemus-dev/gitnr) ⭐ 236 | 🐛 5 | 🌐 Rust | 📅 2026-05-28 - Create `.gitignore` files using one or more templates from TopTal, GitHub or your own collection.
* [git-crecord](https://github.com/andrewshadura/git-crecord) ⭐ 217 | 🐛 21 | 🌐 Python | 📅 2025-05-23 - Git subcommand to interactively select changes to commit or stage.
* [gmap](https://github.com/seeyebe/gmap) ⚠️ Archived - Command-line tool for visualizing Git activity.
* [Git Auto Sync](https://github.com/GitJournal/git-auto-sync) ⭐ 201 | 🐛 17 | 🌐 Go | 📅 2024-07-16 - Automatically commits changes to a git repository, and always keep that repository up to date.
* [patchy](https://github.com/NikitaRevenco/patchy) ⚠️ Archived - A tool which makes it easy to declaratively manage personal forks by automatically merging pull requests.
* [prs](https://github.com/dhth/prs) ⭐ 184 | 🐛 2 | 🌐 Go | 📅 2026-06-08 - Stay updated on PRs without leaving the terminal.
* [git-remote-aws](https://github.com/nathants/git-remote-aws) ⭐ 169 | 🐛 0 | 🌐 Go | 📅 2026-07-18 - Management of encrypted git hosting.
* [semantic-git-commit-cli](https://github.com/JPeer264/node-semantic-git-commit-cli) ⭐ 150 | 🐛 8 | 🌐 JavaScript | 📅 2023-02-12 - Ensure semantic commits messages. With emoji support.
* [git-cc](https://github.com/SKalt/git-cc) ⭐ 141 | 🐛 10 | 🌐 Go | 📅 2026-08-24 - A git extension to help write conventional commits.
* [Kusa](https://github.com/Ryu0118/Kusa) ⭐ 136 | 🐛 2 | 🌐 Rust | 📅 2023-06-25 - Displays GitHub contribution graphs.
* [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) ⭐ 120 | 🐛 4 | 🌐 Swift | 📅 2026-01-18 - Command-line tool for generating Git commit messages and PR descriptions with AI based on Git diffs and commits. Supports staged/unstaged changes and customizable AI parameters.
* [pyautogit](https://github.com/jwlodek/pyautogit) ⭐ 112 | 🐛 3 | 🌐 Python | 📅 2020-07-05 - A TUI for working with git written in python.
* [Export Pull Requests](https://github.com/sshaw/export-pull-requests) ⭐ 108 | 🐛 5 | 🌐 Ruby | 📅 2022-02-11 - Export pull requests and/or issues to a CSV file. Supports GitHub, GitLab, and Bitbucket.
* [gitsnip](https://github.com/dagimg-dot/gitsnip) ⭐ 89 | 🐛 3 | 🌐 Go | 📅 2025-04-19 - A CLI tool to download specific folders from a git repository.
* [travelgrunt](https://github.com/ivanilves/travelgrunt) ⭐ 67 | 🐛 4 | 🌐 Go | 📅 2025-10-04 - cd inside \[mono]repos without fatigue.
* [gh-stars](https://github.com/aymanbagabas/gh-stars) ⭐ 53 | 🐛 4 | 🌐 Go | 📅 2023-11-06 - A GitHub CLI extension to show repository stargazers.
* [git-heatgrid](https://github.com/denshakhov/git-heatgrid) ⭐ 42 | 🐛 0 | 🌐 Shell | 📅 2026-01-29 - Visualize git commits as a calendar heatmap.
* [unreal-git-hook](https://github.com/dmayboroda/unreal-git-hook) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2025-02-12 - Mix of git-hook and Unreal Tournament announcer.
* [mamediff](https://github.com/sile/mamediff) ⭐ 37 | 🐛 0 | 🌐 Rust | 📅 2026-05-21 - A TUI editor for managing unstaged and staged Git diffs.
* [stargazer](https://github.com/gennaro-tedesco/stargazer) ⭐ 37 | 🐛 0 | 🌐 Go | 📅 2022-09-23 - GitHub stats from the command line.
* [gh-repo-man](https://github.com/2KAbhishek/gh-repo-man) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2026-08-09 - GitHub CLI extension that allows developers to browse, clone and work with multiple repositories interactively.
* [gits-statuses](https://github.com/nicolgit/gits-statuses) ⭐ 30 | 🐛 3 | 🌐 Python | 📅 2026-01-13 - A python/powershell command-line tool to display the status of multiple Git repositories in a clear, tabular format.
* [git-identity](https://github.com/cookiengineer/git-identity) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2023-07-18 - Automated git alias management.
* [nodebro](https://github.com/jonaburg/nodebro) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2025-10-09 - Easily view most recent Github releases/tags and release notes from the terminal.
* [Git Commit Vanity Hash Solver](https://github.com/trichner/gitc0ffee) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2025-07-18 - Neat tool to find a 'vanity' hash for a given git commit. Make all your commits hashes start with the prefix c0ffee, cafe, badc0de5 or whatever makes you happy!
* [git-booster-cli](https://github.com/akgondber/git-booster-cli) ⭐ 17 | 🐛 0 | 🌐 TypeScript | 📅 2024-06-14 - Improve your git workflow with customizable and runnable blocks.
* [ur-commit-mentor](https://github.com/ddoemonn/ur-commit-mentor) ⭐ 17 | 🐛 1 | 🌐 Rust | 📅 2025-01-19 - A CLI tool that analyzes git commits and provides AI-powered code review insights (for now only works with Claude API).
* [giq](https://github.com/doganarif/giq) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2026-06-23 - Git CLI with AI-powered commit messages and insights; it is a drop-in replacement for git with the same commands.
* [mkgit](https://github.com/cosmicwanderer7/mkgit) ⭐ 13 | 🐛 1 | 🌐 Shell | 📅 2024-02-26 - This Bash script automates the process of creating a new GitHub repository, initializing it with a README file, and pushing the initial commit to the remote repository. The script prompts the user for a repository name and utilizes the GitHub API to create a new public repository.
* [PReam-Team](https://github.com/nikoladucak/pream-team/) ⭐ 13 | 🐛 5 | 🌐 Python | 📅 2024-02-26 - A TUI utility that helps you keep track of your teams GitHub PRs across multiple repositories.
* [gacp](https://github.com/anhsirk0/gacp) ⭐ 12 | 🐛 0 | 🌐 Perl | 📅 2024-04-14 - git add, commit and push in one go.
* [rcz](https://github.com/Cassin01/rcz) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2023-01-31 - A tool to write a commit message based on “Conventional Commits”.
* [git-all-branches](https://github.com/zacanger/git-all-branches) ⚠️ Archived - Improved visualization of git branches (`git branch -a`).
* [GiTerm](https://github.com/isene/GiTerm) ⭐ 8 | 🐛 0 | 🌐 Ruby | 📅 2026-05-24 - Git and GitHub TUI application (browse repositories, manage issues and pull requests and perform Git operations from the terminal).
* [mamegrep](https://github.com/sile/mamegrep) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-05-21 - An interactive terminal interface for 'git grep' to easily edit search patterns and view results.
* [gitsummary](https://github.com/glenreesor/gitsummary) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-12-08 - A better git status that lists stashes, file statuses, branch list, all nicely formatted with color.
* [automate-git-commands](https://github.com/LEDparty/automate-git-commands) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2026-06-11 - Automates many of the common uses of git, ssh key generation, and ssh configuration.
* [Git Activity Visualization](https://github.com/dakennedyd/activity) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2025-06-02 - Creates a git activity heat map in the command line.
* [Smart Commit](https://github.com/eL1fe/smart-commit) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-12-15 - Customizable CLI tool for creating consistent Git commits using interactive prompts (automatic commit type suggestions, CI integration, GPG signing, push support, and local configuration for a streamlined commit workflow).
* [kick](https://github.com/mcandre/kick) ⚠️ Archived - git sync automator.
* [repo-verify-utils](https://github.com/jaggzh/repo-verify-utils) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-06-01 - Utility collection to help examine what repositories and scopes yout GitHub identity has access to.
* [gh](https://cli.github.com/) - GitHub's official tool to manage repos, issues, projects, gists and much more.
* [git](https://git-scm.com/) - The winner across all the existing file versioning tools, distributed versioning, fully controllable from the command-line, plenty of configuration and usage options, behind a number of related project that leverage git as backend.
* [git-annex](https://git-annex.branchable.com/) - Manages files with `git`, without checking the file contents into git; very useful to manage large/binary files.
* [Gitea](https://gitea.com/) - Single binary self-hosted Git service.
* [hut](https://git.sr.ht/~xenrox/hut) - A CLI tool for sr.ht.

## <a name="versioning"></a>Versioning

Tools for file versioning that are not related to git.

* [Jujutsu](https://github.com/martinvonz/jj) ⭐ 31,177 | 🐛 1,219 | 🌐 Rust | 📅 2026-08-25 - A Git-compatible VCS that is both simple and powerful.
* [Bob](https://github.com/MordechaiHadad/bob) ⭐ 2,140 | 🐛 18 | 🌐 Rust | 📅 2026-08-25 - Bob is a cross-platform and easy-to-use Neovim version manager, allowing for easy switching between versions.
* [cocommit](https://github.com/andrewromanenco/cocommit) ⭐ 149 | 🐛 0 | 🌐 Python | 📅 2025-03-23 - Cocommit is a command-line tool that works with your HEAD commit and leverages an LLM of your choice to enhance commit quality.
* [gee](https://github.com/human37/gee) ⭐ 11 | 🐛 2 | 🌐 Rust | 📅 2021-05-04 - CLI repository manager and automation tool written in rust.
* [Bazaar](http://bazaar.canonical.com/en/) - Multiplatform version control system supporting different workflows; it is part of the GNU Project, and it is free software sponsored by Canonical.
* [fnc](https://fnc.bsdbox.org/index) - Interactive text-based user interface for Fossil.
* [fossil](https://fossil-scm.org/) - A simple, high-reliability, distributed software configuration management system with these advanced features: project management, built-in web interface, friendly self-hosting, simple networking, all-in-one standalone executable, and much more.
* [Mercurial](https://www.mercurial-scm.org/) - Free, distributed source control management tool.
* [myrepo](https://myrepos.branchable.com/) - A repository management tool.

## <a name="programming"></a>Programming

Tools for developers, including debuggers, testing, line counters, boilerplate and license generators, etc..

* [Repomix](https://github.com/yamadashy/repomix) ⭐ 28,040 | 🐛 134 | 🌐 TypeScript | 📅 2026-08-23 - Tool that packs your entire repository into a single, AI-friendly file; Perfect for when you need to feed your codebase to Large Language Models (LLMs) or other AI tools.
* [Crush](https://github.com/charmbracelet/crush) ⭐ 27,650 | 🐛 672 | 🌐 Go | 📅 2026-08-25 - Flexible AI coding agent with a wide range of LLMS, maintains multiple work sessions and contexts per project, works everywhere and extensible.
* [semantic-release](https://github.com/semantic-release/semantic-release) ⭐ 24,003 | 🐛 405 | 🌐 JavaScript | 📅 2026-08-22 - Automates the whole node.js package release workflow including: determining the next version number, generating the release notes, and publishing the package.
* [air](https://github.com/air-verse/air) ⭐ 23,916 | 🐛 4 | 🌐 Go | 📅 2026-08-01 - Live reload for Go apps.
* [cloc](https://github.com/AlDanial/cloc) ⭐ 23,459 | 🐛 26 | 🌐 Perl | 📅 2026-08-08 - Tool for counting blank lines, comment lines, and physical lines of source code in many programming languages.
* [Tokei](https://github.com/XAMPPRocky/tokei) ⭐ 14,849 | 🐛 243 | 🌐 Rust | 📅 2026-05-06 - Tokei is a program that displays statistics about your code. Tokei will show the number of files, total lines within those files and code, comments, and blanks grouped by language.
* [devbox](https://github.com/jetify-com/devbox) ⭐ 12,299 | 🐛 496 | 🌐 Go | 📅 2026-08-18 - Instant, easy, and predictable development environments.
* [gdb-dashboard](https://github.com/cyrus-and/gdb-dashboard) ⭐ 12,241 | 🐛 19 | 🌐 Python | 📅 2026-07-17 - Modular visual interface for GDB in Python.
* [howdoi](https://github.com/gleitz/howdoi) ⭐ 10,838 | 🐛 29 | 🌐 Python | 📅 2026-04-15 - Instant coding answers via the command line.
* [release-it](https://github.com/release-it/release-it) ⭐ 9,034 | 🐛 9 | 🌐 JavaScript | 📅 2026-08-09 - Automate releases for Git repositories and/or Node.js packages.
* [scc](https://github.com/boyter/scc) ⭐ 8,645 | 🐛 25 | 🌐 Go | 📅 2026-08-24 - Sloc Cloc and Code (scc) is a codebase statistics counter. Goal is to be the fastest code counter possible, but also perform COCOMO calculation like sloccount and to estimate code complexity similar to cyclomatic complexity calculators. In short one tool to rule them all.
* [grex](https://github.com/pemistahl/grex) ⭐ 8,172 | 🐛 18 | 🌐 Rust | 📅 2026-02-27 - A command-line tool for generating regular expressions from user-provided test cases.
* [np](https://github.com/sindresorhus/np) ⭐ 7,712 | 🐛 3 | 🌐 JavaScript | 📅 2026-07-30 - A better `npm publish`.
* [blinkenlights](https://github.com/jart/blink) ⭐ 7,572 | 🐛 55 | 🌐 C | 📅 2025-12-10 - TUI that may be used for debugging x86\_64-linux or i8086 programs across platforms.
* [binsider](https://github.com/orhun/binsider) ⭐ 4,401 | 🐛 36 | 🌐 Rust | 📅 2026-08-23 - A TUI for analyzing Linux binaries.
* [rebound](https://github.com/shobrook/rebound) ⭐ 4,115 | 🐛 24 | 🌐 Python | 📅 2022-02-16 - Fetch Stack Overflow results in your terminal when you get an error. Supported languages: Python, Node.js, Ruby, Go, and Java.
* [Flox](https://github.com/flox/flox) ⭐ 4,104 | 🐛 440 | 🌐 Rust | 📅 2026-08-24 - Developer environments you can take with you.
* [PuDB](https://github.com/inducer/pudb) ⭐ 3,248 | 🐛 164 | 🌐 Python | 📅 2026-08-23 - Allows you to debug code right where you write and test it in a terminal.
* [Euporie](https://github.com/joouha/euporie) ⭐ 2,640 | 🐛 15 | 🌐 Python | 📅 2026-08-24 - Allows you to interact with Jupyter kernels, and run Jupyter notebooks - entirely from the terminal.
* [scons](https://github.com/SCons/scons) ⭐ 2,415 | 🐛 656 | 🌐 Python | 📅 2026-08-20 - Software construction tool.
* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,923 | 🐛 16 | 🌐 Rust | 📅 2026-07-28 - A tool to assist you with large-scale codebase refactors, and it supports most of codemod's options. It is focused on improving the use case "I want to use interactive mode to make sure my regex is correct, and then I want to apply the regex everywhere".
* [stepci](https://github.com/stepci/stepci) ⭐ 1,868 | 🐛 73 | 🌐 TypeScript | 📅 2024-08-03 - Automated API Testing and Quality Assurance.
* [cgdb](https://github.com/cgdb/cgdb) ⭐ 1,838 | 🐛 45 | 🌐 C | 📅 2026-02-27 - Console front-end to the GNU debugger.
* [argbash](https://github.com/matejak/argbash) ⭐ 1,483 | 🐛 33 | 🌐 M4 | 📅 2025-07-17 - Bash argument parsing code generator.
* [ChatDBG](https://github.com/plasma-umass/ChatDBG) ⭐ 1,118 | 🐛 10 | 🌐 Python | 📅 2026-07-20 - AI-assisted debugging. Uses AI to answer 'why'.
* [scriptisto](https://github.com/igor-petruk/scriptisto) ⭐ 1,091 | 🐛 10 | 🌐 Rust | 📅 2025-02-08 - A language-agnostic "shebang interpreter" that enables you to write scripts in compiled languages.
* [bencher](https://github.com/bencherdev/bencher) ⭐ 890 | 🐛 157 | 🌐 Rust | 📅 2026-08-24 - Continuous benchmarking, Bencher allows you to track the performance of your code or binary over time and catch performance regressions before you release.
* [sls-dev-tools](https://github.com/Theodo-UK/sls-dev-tools) ⭐ 871 | 🐛 62 | 🌐 JavaScript | 📅 2023-04-25 - Interactive in-terminal dashboard that allows to monitor and manage the resources of  AWS-based Serverless applications.
* [nbterm](https://github.com/davidbrochart/nbterm) ⭐ 779 | 🐛 31 | 🌐 Python | 📅 2023-08-10 - Jupyter Notebooks in the terminal.
* [Kool](https://github.com/kool-dev/kool) ⭐ 724 | 🐛 8 | 🌐 Go | 📅 2026-08-15 - CLI tool that brings the complexities of modern software development making these environments lightweight, fast and reproducible.
* [gup](https://github.com/nao1215/gup) ⭐ 596 | 🐛 2 | 🌐 Go | 📅 2026-08-21 - Update binaries installed by "go install" with goroutines.
* [DevTUI](https://github.com/skatkov/devtui) ⭐ 553 | 🐛 41 | 🌐 Go | 📅 2026-08-24 - All-in-one terminal toolkit that consolidates everyday developer utilities into a unified TUI and CLI.
* [todocheck](https://github.com/preslavmihaylov/todocheck) ⭐ 440 | 🐛 15 | 🌐 Go | 📅 2026-06-13 - Static code analyzer for annotated TODO comments.
* [cgasm](https://github.com/bnagy/cgasm) ⭐ 385 | 🐛 3 | 🌐 PLpgSQL | 📅 2020-09-19 - Pronounced “SeekAzzem”, it is a standalone, offline terminal-based tool with no dependencies that gives me x86 assembly documentation.
* [dtool](https://github.com/guoxbin/dtool) ⭐ 379 | 🐛 3 | 🌐 Rust | 📅 2025-11-24 - Collection of development tools.
* [pproftui](https://github.com/Oloruntobi1/pproftui) ⭐ 280 | 🐛 2 | 🌐 Go | 📅 2025-07-28 - TUI for Go's pprof that makes profiling interactive, intuitive, and fast.
* [lab](https://github.com/lugenx/lab) ⭐ 266 | 🐛 1 | 🌐 Go | 📅 2025-02-01 - Lab helps you experiment with code without friction. Type `lab` with any extension and start coding - it handles files, organization, and cleanup automatically.
* [hors](https://github.com/WindSoilder/hors) ⭐ 248 | 🐛 9 | 🌐 Rust | 📅 2024-04-05 - Instant coding answers via the command line.
* [temci](https://github.com/parttimenerd/temci) ⭐ 199 | 🐛 8 | 🌐 Python | 📅 2025-07-29 - Advanced benchmarking tool written in Python 3 that supports setting up an environment for benchmarking and the generation of visually appealing reports.
* [chars](https://github.com/antifuchs/chars) ⭐ 187 | 🐛 10 | 🌐 Rust | 📅 2026-08-24 - Display names and codes for various ASCII (and Unicode) characters / code points.
* [cargo-seek](https://github.com/tareqimbasher/cargo-seek) ⭐ 186 | 🐛 6 | 🌐 Rust | 📅 2026-08-12 - A TUI for searching, adding and installing cargo crates.
* [mk](https://github.com/pycontribs/mk) ⭐ 139 | 🐛 13 | 🌐 Python | 📅 2026-08-24 - mk is a CLI tool that aims to ease contribution to any open source project by hiding repository implementation details from the casual contributor.
* [pire](https://github.com/johannestaas/pire) ⭐ 125 | 🐛 1 | 🌐 Python | 📅 2019-09-26 - Python Interactive Regular Expressions.
* [suss](https://github.com/shobrook/suss) ⭐ 122 | 🐛 0 | 🌐 Python | 📅 2025-05-01 - AI-powered bug finder that knows your codebase.
* [umake](https://github.com/mcandre/unmake) ⭐ 119 | 🐛 66 | 🌐 Rust | 📅 2026-08-20 - Makefile linter emphasizing portability, targeting the POSIX make standard.
* [termfu](https://github.com/jvalcher/termfu) ⭐ 110 | 🐛 0 | 🌐 C | 📅 2025-10-02 - A multi-language debugger frontend that allows users to create and switch between custom layouts.
* [codegrab](https://github.com/epilande/codegrab) ⭐ 96 | 🐛 4 | 🌐 Go | 📅 2026-01-02 - Interactive CLI tool for selecting and bundling code into a single, LLM-ready output file.
* [Scrut](https://github.com/facebookincubator/scrut) ⭐ 82 | 🐛 8 | 🌐 Rust | 📅 2026-08-24 - A testing toolkit for CLI applications designed to rigorously test terminal programs, inspired by Cram and focuses on providing a straightforward way to validate CLI behaviour.
* [mush](https://github.com/javanile/mush) ⭐ 73 | 🐛 15 | 🌐 Shell | 📅 2026-03-22 - Mush, a build system for shell.
* [dotenvhub](https://github.com/Zaloog/dotenvhub) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2025-12-19 - Terminal App to centrally manage .env files. Written in Python powered by Textual.
* [Tokui](https://github.com/zdyxry/tokui) ⭐ 51 | 🐛 1 | 🌐 Go | 📅 2026-07-30 - An interactive TUI for visualizing code statistics from tockei.
* [sidem](https://github.com/taha-yassine/sidem) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2025-08-11 - TUI app that helps simplifying the management of .env configuration files.
* [PesterExplorer](https://github.com/HeyItsGilbert/PesterExplorer) ⭐ 26 | 🐛 5 | 🌐 PowerShell | 📅 2026-05-30 - A TUI to explore Pester results (prints tests results as they're running).
* [PAR MCP Inspector TUI](https://github.com/paulrobello/par-mcp-inspector-tui) ⭐ 25 | 🐛 11 | 🌐 Python | 📅 2026-06-23 - TUI to inspect and test MCP (model context protocol) servers.
* [dfft](https://github.com/dhth/dfft) ⭐ 20 | 🐛 4 | 🌐 Rust | 📅 2026-06-19 - The program monitors changes as AI agents modify your codebase.
* [pwgo](https://github.com/dennisbergevin/pwgo) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2025-06-26 - Interactive local run replament command for npx playwright test.
* [Leetcode-go](https://github.com/Manan-Prakash-Singh/leetcode-go) ⭐ 12 | 🐛 4 | 🌐 Go | 📅 2023-09-20 - A simple CLI tool for searching, downloading and submitting problems to LeetCode.
* [llm-fuse](https://github.com/antonbelev/llm-fuse) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-02-10 - A tool designed to quickly generate an aggregated text file, or multiple files when chunking is enabled, from numerous files within a repository that can then be pasted into a LLM prompt to provide context from multiple source files.
* [nsh](https://github.com/theHamdiz/nsh) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2024-03-19 - A powerful renaming utility for developers, used to rename Symbols, Phrases in File contents, file names, directory names, recursively, useful specially when you find a better name for your app.
* [CodeMark CLI](https://github.com/rootCircle/codemark-cli) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2023-10-14 - Helps you manage coding assignments and tests; easily initialize the configuration, list assignments, fetch and check your code, submit your code for grading, and get AI-powered error recommendations.
* [Locus](https://github.com/tesso57/locus) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-24 - Locus is a Git-aware, local-first task management CLI, designed to streamline your development workflow, especially when working with AI coding assistants.
* [pvcheck](https://github.com/claudio-unipv/pvcheck) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-10-17 - A tool to apply automated testing to programs that produce textual output. The format of the output is very specific, making pvcheck suitable to test programming quizzes.
* [QuickStart](https://github.com/squach90/homebrew-quickstart) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-03-01 - CLI to quickly create projects in HTML, Python, Node\_js, Bash and more.
* [fmake](https://github.com/bharatvaj/fmake) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2026-03-22 - Brings `make`s interface to almost any build system.
* [Rusty Forge](https://github.com/konni332/rustyforge) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-03-11 - Minimal build manager for C/C++ projects written in Rust; It automates compiling binaries and libraries, sopports parallel builds, profiles, features and manages a build cache.
* [Bump-Setup](https://github.com/talwrii/bump-setup) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-07-07 - Command-line utility designed to automatically update versione numbers in Pyhton project configuration files.
* [bashly](https://bashly.dannyb.co/) - Bashly is a command line application (written in Ruby) that lets you generate feature-rich bash command line tools.
* [Cppcheck](http://cppcheck.net/) - Static analysis tool for C/C++ code providing unique code analysis to detect bugs and focuses on detecting undefined behavior and dangerous coding constructs.
* [dasht](http://sunaku.github.io/dasht/man/man0/README.html) - Search in 200+ offline documentation sets API docs offline, in your terminal or browser.
* [DEM](https://www.axemsolutions.io/dem_doc/index.html) - Containerized Development Environment Manager for embedded development.
* [Frama-C](https://frama-c.com/) - Open source extensible and collaborative platform dedicated to source-code analysis of C software. Frama-C can assist from the navigation through unfamiliar projects up to the certification of critical software.
* [Lazymake](https://lazymake.vercel.app/) - Modern TUI for Makefiles with interactive target selection, dependency visualization, and command safety analysis.
* [minify.js](https://github.com/adamlui/minify.js/#readme) - Recursively minify all JavaScript files.
* [o](https://github.com/rev-dot-now/o) - Agentic Design Framework, automate with natural language, build agents in seconds, self-generate new features.
* [rr](https://rr-project.org/) - Debug the recording, deterministically, as many times as you want.

## <a name="programming-boilerplate"></a>Program templates and boilerplate

Utilities that generate licenses, documentation structure (README files), project directories and other boilerplate for software projects.

* [Cookiecutter](https://github.com/cookiecutter/cookiecutter) ⭐ 25,065 | 🐛 313 | 🌐 Python | 📅 2026-04-01 - A cross-platform command-line utility that creates projects from cookiecutters (project templates), e.g. Python package projects, C projects.
* [readme-md-generator](https://github.com/kefranabg/readme-md-generator) ⭐ 11,129 | 🐛 30 | 🌐 JavaScript | 📅 2022-09-20 - CLI that generates beautiful README.md files.
* [boilr](https://github.com/tmrts/boilr) ⭐ 1,763 | 🐛 44 | 🌐 Go | 📅 2023-03-07 - Boilerplate template manager that generates files or directories from template repositories.
* [clog](https://github.com/clog-tool/clog-cli) ⭐ 920 | 🐛 27 | 🌐 Rust | 📅 2024-08-15 - Creates a changelog automatically from local git metadata.
* [add-gitignore](https://github.com/TejasQ/add-gitignore) ⭐ 730 | 🐛 5 | 🌐 JavaScript | 📅 2023-11-20 - Interactively generate a .gitignore for software projects.
* [legit](https://github.com/captainsafia/legit) ⭐ 590 | 🐛 10 | 🌐 JavaScript | 📅 2019-05-20 - Automagically generates a LICENSE file for the current working directory that you are in or a license header for a file where applicable.
* [kickstart](https://github.com/Keats/kickstart) ⭐ 473 | 🐛 14 | 🌐 Rust | 📅 2025-12-21 - Scaffolding tool to get new projects up and running quickly.
* [mklicense](https://github.com/cezaraugusto/mklicense) ⭐ 207 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-13 - CLI tool for easily generating the text of the most common licenses.
* [Proji](https://github.com/nikoksr/proji) ⭐ 202 | 🐛 3 | 🌐 Go | 📅 2022-12-30 - Powerful cross-platform CLI project templating tool.
* [license-up](https://github.com/nikitavoloboev/license-up) ⭐ 109 | 🐛 3 | 🌐 Go | 📅 2024-01-22 - Create a license quickly for a given name.
* [lichen](https://github.com/philocalyst/lichen) ⭐ 17 | 🐛 1 | 🌐 Rust | 📅 2026-02-03 - Lichen provides tools for producing and managing licenses both on the CLI and through a config file. Double license and only license particular parts of a codebase with regex.
* [contributing-generator](https://github.com/friedrith/contributing-generator) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2025-03-07 - A generator for the CONTRIBUTING.md, README.md, LICENSE, etc.
* [upnup](https://github.com/tomit4/upnup) ⭐ 4 | 🐛 0 | 🌐 Roff | 📅 2022-12-20 - A command line utility that generates a LICENSE file in the current working directory.

## <a name="devops"></a>DevOps

Applications for supporting DevOps tasks, such as containers or cloud systems management.

* [k9s](https://github.com/derailed/k9s) ⭐ 34,422 | 🐛 104 | 🌐 Go | 📅 2026-08-24 - Kubernetes CLI To Manage Your Clusters In Style!
* [Devbox](https://github.com/jetpack-io/devbox) ⭐ 12,299 | 🐛 496 | 🌐 Go | 📅 2026-08-18 - Devbox is a command-line tool that lets you easily create isolated shells and containers by defining the list of packages required by the environment.
* [SAWS](https://github.com/donnemartin/saws) ⭐ 5,302 | 🐛 39 | 🌐 Python | 📅 2024-04-02 - A supercharged AWS command line interface (CLI).
* [stern](https://github.com/stern/stern) ⭐ 4,845 | 🐛 41 | 🌐 Go | 📅 2026-08-19 - Multi pod and container log tailing for Kubernetes.
* [KDash](https://github.com/kdash-rs/kdash) ⭐ 2,525 | 🐛 2 | 🌐 Rust | 📅 2026-08-19 - A simple and fast terminal dashboard for Kubernetes.
* [eks-node-viewer](https://github.com/awslabs/eks-node-viewer/) ⭐ 1,636 | 🐛 24 | 🌐 Go | 📅 2026-08-24 - Tool for visualizing dynamic node usage within a kubernetes cluster.
* [OPS](https://github.com/nanovms/ops) ⭐ 1,511 | 🐛 143 | 🌐 Go | 📅 2026-08-23 - Ops is a tool for creating and running a [Nanos](https://github.com/nanovms/nanos) ⭐ 3,184 | 🐛 81 | 🌐 C | 📅 2026-08-22 unikernel. It is used to package, create, and run your application as a [Nanos](https://github.com/nanovms/nanos) ⭐ 3,184 | 🐛 81 | 🌐 C | 📅 2026-08-22 unikernel instance.
* [lazyjournal](https://github.com/Lifailon/lazyjournal) ⭐ 1,388 | 🐛 7 | 🌐 Go | 📅 2026-08-01 - Terminal user interface for reading logs from journald, auditd, file system, Docker (including Swarm) containers, Compose stacks, Podman and Kubernetes pods with support for output coloring and multiple filtering modes.
* [TFTUI](https://github.com/idoavrah/terraform-tui) ⭐ 1,290 | 🐛 12 | 🌐 Python | 📅 2024-07-09 - TUI to view and interact with Terraform state.
* [podman-tui](https://github.com/containers/podman-tui) ⭐ 1,205 | 🐛 17 | 🌐 Go | 📅 2026-08-24 - TUI for Podman environment.
* [ktop](https://github.com/vladimirvivien/ktop) ⭐ 1,104 | 🐛 11 | 🌐 Go | 📅 2026-07-03 - Tool that displays useful metrics information about nodes, pods, and other workload.
* [sen](https://github.com/TomasTomecek/sen) ⭐ 1,050 | 🐛 35 | 🌐 Python | 📅 2025-08-12 - TUI for containers (manages interactively and inspects containers, dashboard view for containers and images, searching and filtering, real-time updates, tree view of all images).
* [Amazon EC2 Instance Selector](https://github.com/aws/amazon-ec2-instance-selector) ⭐ 933 | 🐛 20 | 🌐 Go | 📅 2025-12-22 - A CLI tool and go library which recommends instance types based on resource criteria like vcpus and memory.
* [E1S](https://github.com/keidarcy/e1s) ⭐ 920 | 🐛 2 | 🌐 Go | 📅 2026-08-03 - TUI for browsing and managing AWS ECS resources.
* [Ducker](https://github.com/robertpsoane/ducker) ⭐ 919 | 🐛 15 | 🌐 Rust | 📅 2026-08-03 - TUI for managing docker containers.
* [PUG](https://github.com/leg100/pug) ⭐ 694 | 🐛 21 | 🌐 Go | 📅 2026-01-02 - TUI for Terraform (perform tasks in parallel, manage state resources, calculate costs, automatically loads workspace variable files).
* [kubetui](https://github.com/sarub0b0/kubetui) ⭐ 393 | 🐛 11 | 🌐 Rust | 📅 2026-08-22 - A TUI tool designed for monitoring Kubernetes resources.
* [mkdkr](https://github.com/rosineygp/mkdkr) ⭐ 382 | 🐛 0 | 🌐 Shell | 📅 2021-05-27 - Super small and powerful framework for build CI pipeline, scripted with Makefile and isolated with docker.
* [lazycontainer](https://github.com/andreybleme/lazycontainer) ⭐ 370 | 🐛 8 | 🌐 Go | 📅 2026-08-17 - TUI for managing Apple containers.
* [planor](https://github.com/mrusme/planor) ⚠️ Archived - The Cloud Aviator: TUI client for cloud services (AWS, Vultr, Heroku, Render.com, Fleek, ...).
* [kubectx](https://kubectx.dev/) - Quickly switch between clusters and namespaces in kubectl.
* [kubefwd](https://kubefwd.com) - Bulk port forwarding Kubernetes services to localhost with unique IPs per service and interactive TUI.

## <a name="webdev"></a>Web development

Web development tools, including load test tools, API clients and managers, link checkers and extractors, etc..

* [HTTPie](https://github.com/httpie/httpie) ⭐ 38,448 | 🐛 332 | 🌐 Python | 📅 2024-12-17 - HTTPie for Terminal: human-friendly CLI HTTP client for the API era.
* [monolith](https://github.com/Y2Z/monolith) ⭐ 15,446 | 🐛 73 | 🌐 Rust | 📅 2026-05-25 - Tool and library for saving complete web pages as a single HTML file.
* [posting](https://github.com/darrenburns/posting) ⭐ 12,308 | 🐛 83 | 🌐 Python | 📅 2026-03-25 - The modern API client that lives in your terminal, not unlike Postman and Insomnia.
* [s3cmd](https://github.com/s3tools/s3cmd) ⭐ 4,905 | 🐛 311 | 🌐 Python | 📅 2025-10-22 - Command line tool for managing Amazon S3 and CloudFront services.
* [lychee](https://github.com/lycheeverse/lychee) ⭐ 3,851 | 🐛 78 | 🌐 Rust | 📅 2026-08-24 - Fast, async, resource-friendly link checker written in Rust.
* [snallygaster](https://github.com/hannob/snallygaster) ⭐ 2,110 | 🐛 12 | 🌐 Python | 📅 2026-02-04 - Tool to scan for secret files on HTTP servers.
* [tldx](https://github.com/brandonyoungdev/tldx) ⭐ 1,915 | 🐛 7 | 🌐 Go | 📅 2026-08-21 - Domain Availability Research Tool.
* [pageres-cli](https://github.com/sindresorhus/pageres-cli) ⭐ 1,743 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-09 - Capture screenshots of websites in various resolutions. A good way to make sure your websites are responsive.
* [urlhunter](https://github.com/utkusen/urlhunter) ⭐ 1,697 | 🐛 0 | 🌐 Go | 📅 2025-01-23 - Recon tool that allows searching on URLs that are exposed via shortener services.
* [Slumber](https://github.com/LucasPickering/slumber) ⭐ 1,219 | 🐛 9 | 🌐 Rust | 📅 2026-07-04 - TUI-based HTTP/REST client.
* [linkchecker](https://github.com/linkchecker/linkchecker) ⭐ 1,075 | 🐛 96 | 🌐 Python | 📅 2026-07-28 - Check links in web documents or full websites.
* [beachpatrol](https://github.com/sebastiancarlos/beachpatrol) ⭐ 919 | 🐛 4 | 🌐 JavaScript | 📅 2025-10-30 - A CLI tool to replace and automate your everyday web browser.
* [Discharge](https://github.com/brandonweiss/discharge) ⭐ 647 | 🐛 20 | 🌐 JavaScript | 📅 2021-04-09 - Deploy static websites to Amazon S3.
* [ain](https://github.com/jonaslu/ain) ⭐ 621 | 🐛 1 | 🌐 Go | 📅 2025-10-17 - An HTTP API client for the terminal.
* [is-up-cli](https://github.com/sindresorhus/is-up-cli) ⭐ 366 | 🐛 1 | 🌐 JavaScript | 📅 2022-04-23 - Check whether a website is up or down using the [isitup.org](https://isitup.org/) API.
* [crawley](https://github.com/s0rg/crawley) ⭐ 341 | 🐛 8 | 🌐 Go | 📅 2026-08-21 - Unix-way web crawler: crawls web pages and prints any link it can find.
* [kanha](https://github.com/pwnwriter/kanha) ⭐ 324 | 🐛 7 | 🌐 Rust | 📅 2025-01-08 - A web-app pentesting suite written in Rust.
* [domain-check](https://github.com/saidutt46/domain-check) ⭐ 304 | 🐛 4 | 🌐 Rust | 📅 2026-05-14 - Universal domain exploration engine: fast domain availability checks across the internet.
* [django-tui](https://github.com/anze3db/django-tui) ⭐ 296 | 🐛 1 | 🌐 Python | 📅 2024-10-16 - Inspect and run Django Commands in a text-based user interface (TUI).
* [iola](https://github.com/pvarentsov/iola) ⭐ 170 | 🐛 0 | 🌐 TypeScript | 📅 2023-10-12 - A command-line socket client with REST API. It helps to work with socket servers using your favorite REST client.
* [http-tanker](https://github.com/PierreKieffer/http-tanker) ⭐ 78 | 🐛 0 | 🌐 Go | 📅 2026-02-18 - Terminal application used for API testing; easily create, manage and execute HTTP requests from the terminal.
* [dummy](https://github.com/sterrasec/dummy) ⭐ 68 | 🐛 2 | 🌐 Python | 📅 2025-02-12 - Generator of static files for testing file upload. It can generate the PNG file of any number of bytes!
* [viewport-list-cli](https://github.com/kevva/viewport-list-cli) ⭐ 60 | 🐛 1 | 🌐 JavaScript | 📅 2016-01-06 - Return a list of devices and their viewports.
* [Ballast](https://github.com/synoet/ballast) ⭐ 48 | 🐛 1 | 🌐 Rust | 📅 2025-07-03 - A simple API load testing tool that lets you compare performance snapshots of your API.
* [cnTUI](https://github.com/fipso/cntui) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2023-07-14 - Replay chrome requests from your terminal using curl.
* [Reachable](https://github.com/italolelis/reachable) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2021-07-03 - Check if a domain is up.
* [Shopify Development Tools](https://github.com/ScreenStaring/shopify-dev-tools) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2026-08-24 - Tools to assist with the development and/or maintenance of Shopify apps and stores.
* [xpe](https://github.com/charmparticle/xpe) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2025-05-12 - A command-line xpath tool that is easy to use.
* [maelstrom](https://github.com/twentyone24/maelstrom) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2024-08-25 - stress-test your API reliability on concurrent threads, with latency metrics.
* [restbook](https://github.com/shalev007/restbook) ⭐ 16 | 🐛 7 | 🌐 Python | 📅 2025-04-22 - RestBook is an open-source CLI tool for orchestrating complex API workflows using simple YAML playbooks.
* [qwicket](https://github.com/hardfau1t/qwicket) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2025-01-02 - Commandline API development ecosystem.
* [Hugo](https://gohugo.io/) - The world's fastest framework for building websites.
* [Metalsmith](http://www.metalsmith.io/) - An extremely simple static site generator, all functionalities are provided by plugins that can be combined and chained, written and extendable in JavaScript.
* [Mycorrhiza Wiki](https://mycorrhiza.wiki/) - A lightweight file-system wiki engine that uses Git for keeping history.
* [nanoc](http://nanoc.ws/) - Static site generator written in Ruby, extremely powerful and customizable, support many formats to generate HTML content.
* [surge](https://surge.sh) - Static web publishing on surge.sh CDN.
* [Tsung](http://tsung.erlang-projects.org/) - A multi-protocol distributed load testing tool that can be used to stress HTTP, WebDAV, SOAP, PostgreSQL, MySQL, LDAP and Jabber/XMPP servers.

## <a name="copilot"></a>Co-pilot

Programs that use LLMs to generate commands at the command line or code in general from natural language.

* [Open Interpreter](https://github.com/KillianLucas/open-interpreter) ⭐ 68,138 | 🐛 5 | 🌐 Rust | 📅 2026-08-20 - OpenAI's Code Interpreter in your terminal, running locally.
* [aider](https://github.com/paul-gauthier/aider) ⭐ 48,463 | 🐛 1,824 | 🌐 Python | 📅 2026-05-22 - aider is AI pair programming in your terminal.
* [Yai](https://github.com/ekkinox/yai) ⭐ 869 | 🐛 28 | 🌐 Go | 📅 2024-07-31 - Yai (your AI) is an assistant for your terminal, using OpenAI ChatGPT to build and run commands for you.
* [gpt-do](https://github.com/yasyf/gpt-do) ⭐ 211 | 🐛 2 | 🌐 Python | 📅 2026-07-31 - This is a handy-dandy CLI for when you don't know wtf to do; instead of furiously grepping through man pages, simply use do (or ddo if on bash/zsh), and have GPT-3 do all the magic for you.
* [Llama Terminal Completion](https://github.com/adammpkins/llama-terminal-completion) ⭐ 193 | 🐛 1 | 🌐 Go | 📅 2026-05-31 - Application that interacts with the llama.cpp library to provide virtual assistant capabilities through the command line. It allows you to ask questions and receive intelligent responses, as well as generate Linux commands based on your prompts.
* [CLI Co-Pilot](https://github.com/AntonOsika/CLI-Co-Pilot) ⭐ 191 | 🐛 2 | 🌐 Python | 📅 2023-06-27 - CLI tool that uses GPT4 to turn natural language commands into their Bash/ZShell/PowerShell equivalents.
* [shy-sh](https://github.com/mceck/shy-sh) ⭐ 55 | 🐛 0 | 🌐 Python | 📅 2025-09-16 - Shell AI copilot.
* [aido-cli](https://github.com/kris7ian/aido-cli) ⭐ 36 | 🐛 0 | 🌐 Rust | 📅 2022-11-09 - Looks another interface to online GPT models to execute command through natural language. Very poor documentation and readme, though.
* [aish](https://github.com/chr15m/aish) ⭐ 36 | 🐛 0 | 🌐 Shell | 📅 2025-10-11 - A program that retrieve shell script one-liners, ready to be executed in the terminal.
* [Smart-Shell](https://github.com/Lusan-sapkota/smart-shell) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2025-07-07 - Intelligent terminal assistant that converts natural language into executable Bash or Zsh commands using Gemini AI model via google-genai SDK.
* [Commandpilot](https://github.com/barthr/commandpilot) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-03-12 - An assistant which uses ChatGPT to aid in constructing commands for bash.
* [codemancer](https://0xmmo.github.io/codemancer/) - Code with GPT-4 from your command line.

# <a name="System-and-Terminal"></a>System and Terminal

## <a name="system"></a>System tools

System management tools, such as for brightness control, dotfile and environment variable management, notifications, etc..

* [just](https://github.com/casey/just) ⭐ 35,455 | 🐛 170 | 🌐 Rust | 📅 2026-08-20 - Handy way to save and run project-specific commands.
* [mackup](https://github.com/lra/mackup) ⭐ 15,314 | 🐛 294 | 🌐 Python | 📅 2026-06-15 - Keep your application settings in sync (OS X/Linux).
* [inshellisense](https://github.com/microsoft/inshellisense) ⭐ 10,674 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-24 - IDE style command line auto complete with support for 600+ command line tools.
* [auto-cpufreq](https://github.com/AdnanHodzic/auto-cpufreq) ⭐ 7,738 | 🐛 78 | 🌐 Python | 📅 2026-08-24 - Automatic CPU speed and power optimizer for Linux, which allows to dynamically change the settings of the CPU to save energy and extend the battery life on laptops.
* [fkill-cli](https://github.com/sindresorhus/fkill-cli) ⭐ 7,000 | 🐛 6 | 🌐 JavaScript | 📅 2025-11-09 - Simple cross-platform process killer.
* [Ntfy](https://github.com/dschep/ntfy) ⭐ 4,978 | 🐛 104 | 🌐 Python | 📅 2025-10-27 - Cross-platform Python utility that enables you to automatically get desktop notifications on demand or when long-running commands complete. It can as well send push notifications to your phone once a particular command completes.
* [landrun](https://github.com/Zouuup/landrun) ⭐ 2,273 | 🐛 5 | 🌐 Go | 📅 2026-07-23 - Run any Linux process in a secure, unprivileged sandbox using Landlock. Think firejail, but lightweight, user-friendly, and baked into the kernel.
* [systemctl-tui](https://github.com/rgwood/systemctl-tui) ⭐ 2,037 | 🐛 6 | 🌐 Rust | 📅 2026-07-27 - A fast simple TUI for interacting with systemd services and their logs.
* [sysz](https://github.com/joehillen/sysz) ⭐ 1,882 | 🐛 5 | 🌐 Shell | 📅 2024-04-22 - fzf terminal UI for systemctl.
* [killport](https://github.com/jkfran/killport) ⭐ 1,838 | 🐛 1 | 🌐 Rust | 📅 2026-08-24 - A command-line tool to easily kill processes running on a specified port.
* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,462 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to sysctl(8) with a terminal user interface.
* [brightnessctl](https://github.com/Hummer12007/brightnessctl) ⭐ 1,257 | 🐛 24 | 🌐 C | 📅 2024-12-16 - Read and control device brightness. Devices, by default, include backlight and LEDs - searched for in corresponding classes.
* [tufw](https://github.com/peltho/tufw) ⭐ 855 | 🐛 4 | 🌐 Go | 📅 2026-06-08 - Terminal UI for the UFW Linux firewall.
* [immortal](https://github.com/immortal/immortal) ⭐ 837 | 🐛 2 | 🌐 Go | 📅 2026-08-16 - A \*nix cross-platform (OS agnostic) supervisor.
* [has](https://github.com/kdabir/has) ⭐ 818 | 🐛 20 | 🌐 Shell | 📅 2026-02-26 - Checks presence of various command line tools on the PATH and reports their installed version.
* [qman](https://github.com/plp13/qman) ⭐ 596 | 🐛 13 | 🌐 C | 📅 2026-03-17 - A more modern man page viewer for our terminals.
* [damon](https://github.com/hashicorp/damon) ⭐ 486 | 🐛 9 | 🌐 Go | 📅 2026-08-24 - TUI interface for Hashicorp Nomad, it provides functionality to observe and interact with Nomad resources such as Jobs, Deployments, or Allocations.
* [wander](https://github.com/robinovitch61/wander) ⭐ 480 | 🐛 4 | 🌐 Go | 📅 2024-06-18 - HashiCorp Nomad terminal client.
* [argc-completions](https://github.com/sigoden/argc-completions) ⭐ 456 | 🐛 2 | 🌐 Shell | 📅 2024-11-27 - Autocompletion for any shell and any command.
* [kill-tabs](https://github.com/sindresorhus/kill-tabs) ⭐ 393 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-01 - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory.
* [dtui](https://github.com/Troels51/dtui) ⭐ 316 | 🐛 1 | 🌐 Rust | 📅 2026-08-23 - Small TUI for introspecting the state of the system/session dbus.
* [bashmount](https://github.com/jamielinux/bashmount) ⭐ 290 | 🐛 11 | 🌐 Shell | 📅 2022-06-30 - Tool to mount and unmount removable media from the command-line with a nice interface to list the available options..
* [sysm](https://github.com/jafarlihi/sysm) ⭐ 214 | 🐛 0 | 🌐 C++ | 📅 2026-05-02 - Makes your system play custom sounds when any configured system or external event happens.
* [shournal](https://github.com/tycho-kirchner/shournal) ⭐ 212 | 🐛 4 | 🌐 C++ | 📅 2025-04-10 - Log shell-commands and used files. Snapshot executed scripts. Fully automatic.
* [ugm](https://github.com/ariasmn/ugm) ⭐ 163 | 🐛 1 | 🌐 Go | 📅 2026-04-27 - A terminal based UNIX user and group browser.
* [htui](https://github.com/PierreKieffer/htui) ⭐ 123 | 🐛 1 | 🌐 Go | 📅 2021-04-26 - Heroku Terminal User Interface: manage your apps, scale your dynos, browse logs in real time...
* [empiriqa](https://github.com/ynqa/empiriqa) ⭐ 120 | 🐛 5 | 🌐 Rust | 📅 2025-07-11 - empiriqa (command name is epiq) is a tool for interactively manipulating UNIX pipelines.
* [active-win-cli](https://github.com/sindresorhus/active-win-cli) ⭐ 69 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-30 - Get the title/id/etc of the active window.
* [rs-env](https://github.com/sysid/rs-env) ⭐ 42 | 🐛 0 | 🌐 Rust | 📅 2026-07-16 - Hierarchical environment variable management, compiling the resulting set of from a hierarchical list of `<name>.env` files.
* [trek](https://github.com/franckverrot/trek) ⭐ 32 | 🐛 1 | 🌐 Go | 📅 2023-08-30 - ncurses TUI explorer for Hashicorp Nomad clusters.
* [rfsh](https://github.com/docsion/rfsh) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2023-12-14 - Run shell scripts in batch, concurrently, fully customized with variable.
* [fzf-kill](https://github.com/Zeioth/fzf-kill) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2024-09-02 - The no-nonsense task killer for your terminal.
* [Rumos](https://github.com/octagony/rumos) ⭐ 17 | 🐛 2 | 🌐 Rust | 📅 2023-07-27 - CLI utility for controlling screen brightness.
* [Marstui-rustio](https://github.com/schooldanlp6/marstui-rustio) ⭐ 15 | 🐛 3 | 🌐 Rust | 📅 2025-09-30 - A nice audio management Interface, similar to pavucontrol with the benefit of customizing everything.
* [ntfyme](https://github.com/AnirudhG07/ntfyme) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2024-10-08 - Simple to use, cross platform notification tool which sends you local, gmail, telegram, etc notification when a long running process ends with detailed diagnostics, along with features like tracking for suspended process and terminate them automatically.
* [oswriter](https://github.com/TheSoftwareWizard/oswriter) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2025-05-04 - A command-line tool for creating bootable USB drives from various operating system images.
* [diskroaster](https://github.com/favoritelotus/diskroaster) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2026-08-20 - Multi-threaded disk testing utility that writes and verifies data on a raw disk device (designed to stress-test hard drives and SSDs by dividing the disk into sections, writing data in parallel using multiple threads and verifying the written content).
* [joshfile](https://github.com/if-not-nil/joshfile) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2025-05-10 - Makefiles for those who dont want makefiles: specifies dependencies and commands via YAML configuration file.
* [Kill](https://github.com/unsigned-enby/Kill) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-12-07 - Small bash-only script for killing processes/sending signals.
* [rufl](https://github.com/mobydeck/rufl) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2025-03-14 - RunFlow (rufl) is a command line tool that allows executing other commands either in parallel or sequentially.
* [checksum.sh](https://checksum.sh/) - Checksum.sh is a simple way to download, review, and verify install scripts. If the checksum is OK the script will be printed to stdout, which can be piped to sh or elsewhere.
* [conspy](http://conspy.sourceforge.net/) - "Conspy allows a (possibly remote) user to see what is displayed on a Linux virtual console, and send keystrokes to it."
* [direnv](https://direnv.net/) - Loads and unloads environment variables depending on the current directory.
* [lshw](http://www.ezix.org/project/wiki/HardwareLiSter) - A small tool to provide detailed information on the hardware configuration of the machine. It can report exact memory configuration, firmware version, mainboard configuration, CPU version and speed, cache configuration, bus speed, etc.
* [x-cmd](https://www.x-cmd.com/) - A toolset implemented using posix shell and awk offering many interesting features and that is very small in size.

## <a name="terminal"></a>Terminals

Terminal emulators and related tools.

* [ghostty](https://github.com/ghostty-org/ghostty/) ⭐ 60,180 | 🐛 237 | 🌐 Zig | 📅 2026-08-24 - A fast, feature-rich, and cross-platform terminal emulator that uses platform-native UI and GPU acceleration.
* [wezterm](https://github.com/wez/wezterm) ⭐ 28,533 | 🐛 1,823 | 🌐 Rust | 📅 2026-08-24 - A GPU-accelerated cross-platform terminal emulator and multiplexer implemented in Rust with tons of features.
* [warp](https://github.com/spolu/warp) ⭐ 1,618 | 🐛 12 | 🌐 Go | 📅 2018-03-06 - Secure and simple terminal sharing.
* [Textual Web](https://github.com/Textualize/textual-web) ⭐ 1,446 | 🐛 23 | 🌐 Python | 📅 2024-08-30 - Run TUIs and terminals in your browser.
* [dtach](https://github.com/crigler/dtach) ⭐ 739 | 🐛 20 | 🌐 C | 📅 2025-06-21 - A program written in C that emulates the detach feature of screen.
* [tvterm](https://github.com/magiblot/tvterm) ⭐ 276 | 🐛 8 | 🌐 C++ | 📅 2026-08-14 - A terminal emulator that runs in your terminal (Unix and Windows).
* [wterm](https://github.com/TornadoCookie/wterm) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2024-02-11 - A native Wayland terminal emulator based on an st fork using wld.
* [abduco](https://www.brain-dump.org/projects/abduco) - abduco provides session management i.e. it allows programs to be run independently of their controlling terminal.
* [alacritty](https://alacritty.org) - A GPU-Accelerated terminal emulator that comes with sensible defaults, but allows for extensive configuration.
* [dvtm](https://www.brain-dump.org/projects/dvtm) - Dynamic console window manager that enables dynamic tiling window management for multiple terminal applications.
* [extraterm](https://extraterm.org/) - The swiss army chainsaw of terminal emulators.
* [kitty](https://sw.kovidgoyal.net/kitty/) - A fast, feature-rich, GPU based terminal emulator.
* [mlterm](https://mlterm.sourceforge.net/) - A very fast low latency terminal emulator with features such as rendering variable width fonts, proper bidirectional support out of the box, a daemon mode, multiple XIM, and true background transparency.
* [st](https://st.suckless.org/) - A simple terminal implementation for X.

## <a name="terminal-mux"></a>Terminal multiplexers and accessories

Terminal multiplexers and tools or plugin for multiplexers.

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,095 | 🐛 1,871 | 🌐 Rust | 📅 2026-08-24 - A workspace aimed at developers, ops-oriented people and anyone who loves the terminal. At its core, it is a terminal multiplexer.
* [vtm](https://github.com/netxs-group/vtm) ⭐ 3,358 | 🐛 21 | 🌐 C++ | 📅 2026-07-31 - Virtual terminal multiplexer with window manager and session sharing.
* [vtm](https://github.com/directvt/vtm) ⭐ 3,358 | 🐛 21 | 🌐 C++ | 📅 2026-07-31 - Virtual terminal multiplexer delivered as a single executable; It runs in native Windows or standard consoles, wraps any CLI app and supports infinite nesting to create a text-based desktop that bridges the gap between TUI and GUI.
* [mtm](https://github.com/deadpixi/mtm) ⭐ 1,221 | 🐛 43 | 🌐 C | 📅 2024-07-18 - Micro Terminal Multiplexer - Simple but usable, stable and minimalistic terminal multiplexer.
* [mynav](https://github.com/GianlucaP106/mynav) ⭐ 251 | 🐛 11 | 🌐 Go | 📅 2025-09-28 - A powerful terminal-based workspace navigator and session manager built in Go, MyNav helps developers organize and manage multiple projects through an intuitive interface, seamlessly integrating with tmux sessions.
* [tmux-nested](https://github.com/niqodea/tmux-nested) ⭐ 75 | 🐛 0 | 🌐 Shell | 📅 2025-01-07 - Plugin for nested tmux workflows.
* [peaches](https://github.com/KCaverly/peaches) ⭐ 15 | 🐛 3 | 🌐 Rust | 📅 2023-03-24 - A smart switcher for the terminal. Based on tmux.
* [tmux-session](https://github.com/BartSte/tmux-session) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2024-04-11 - Manage tmux sessions using fzf.
* [byobu](http://byobu.co/) - A text-based window manager and terminal multiplexer; it features enhanced profiles, convenient keybindings, configuration utilities, and toggle-able system status notifications; compatible with `screen` and `tmux`.
* [mx](https://gitlab.com/lpireyn/mx) - A tmux session manager written as a single Bash script.
* [screen](https://www.gnu.org/software/screen/) - Terminal multiplexer that split a physical terminal between several processes, typically interactive shells.
* [Tmate](https://tmate.io/) - A fork of tmux that allows sharing the terminal with other users. AFAIK, it connects to a centralized server to establish the connection. Someone may see this inconvenient for privacy issues.
* [tmux](https://tmux.github.io/) - Terminal multiplexer; born to improve `screen`; client-server architecture, `vi` and `emacs` key-bindings, search in window feature and many more.

## <a name="shells"></a>Shells

Shell programs that enable the interaction through the terminal.

* [Nushell](https://github.com/nushell/nushell) ⭐ 40,328 | 🐛 1,434 | 🌐 Rust | 📅 2026-08-24 - A modern shell written in Rust, where all data is structured.
* [Elvish](https://github.com/elves/elvish) ⭐ 6,364 | 🐛 350 | 🌐 Go | 📅 2026-03-31 - Elvish is a versatile interactive shell and expressive programming language, combined into one seamless package.
* [Oils](https://github.com/oilshell/oil) ⭐ 3,383 | 🐛 610 | 🌐 Python | 📅 2026-05-31 - From their README: "Oils is our upgrade path from bash to a better language and runtime!"
* [Ion](https://github.com/redox-os/ion) ⭐ 1,656 | 🐛 60 | 🌐 Rust | 📅 2026-05-02 - Ion is a modern system shell that features a simple, yet powerful, syntax.
* [dune](https://github.com/adam-mcdaniel/dune) ⭐ 1,084 | 🐛 26 | 🌐 Rust | 📅 2025-06-19 - A customizable shell that aims to be cozy.
* [Twin](https://github.com/cosmos72/twin) ⭐ 1,056 | 🐛 37 | 🌐 C | 📅 2026-08-03 - Text mode window environment. A "retro" program for embedded or remote systems, that doubles as X11 terminal and text-mode equivalent of VNC server.
* [sshrc](https://github.com/cdown/sshrc) ⭐ 528 | 🐛 4 | 🌐 Shell | 📅 2023-01-27 - The program works just like ssh while also sourcing your local sshrc configuration file upon logging in remotely.
* [Cat9](https://github.com/letoram/cat9) ⭐ 526 | 🐛 3 | 🌐 Lua | 📅 2025-05-03 - Cat9 is a user shell script for LASH - a command-line shell that discriminates against terminal emulators, written in Lua.
* [oksh](https://github.com/ibara/oksh) ⭐ 453 | 🐛 17 | 🌐 C | 📅 2026-06-10 - Portable OpenBSD ksh.
* [ksh93](https://github.com/ksh93/ksh) ⭐ 279 | 🐛 72 | 🌐 C | 📅 2026-08-17 - (KornShell) a shell programming language that is compatible with the Bourne Shell in addition and has the major command-entry features of the BSD shell csh.
* [Reptyl](https://github.com/0ut0flin3/Reptyl) ⭐ 144 | 🐛 1 | 🌐 Python | 📅 2023-04-12 - A cross-platform command line shell that supports execution of commands in natural language.
* [cosh](https://github.com/tomhrr/cosh) ⭐ 136 | 🐛 18 | 🌐 Rust | 📅 2026-01-22 - Concatenative command-line shell.
* [N-Commodore](https://github.com/psprint/n-commodore) ⭐ 46 | 🐛 2 | 🌐 Shell | 📅 2023-08-05 - A novel file manager/shell/command-line, where everything is panelized, greppable and remembered.
* [arsh](https://github.com/sekiguchi-nagisa/arsh) ⭐ 29 | 🐛 52 | 🌐 C++ | 📅 2026-08-24 - A statically typed scripting language with shell-like features.
* [Bash](https://www.gnu.org/software/bash/) - (Bourne Again SHell) The most widespread system shell to date.
* [DASH](http://gondor.apana.org.au/~herbert/dash/) - DASH is a POSIX-compliant implementation of /bin/sh that aims to be as small as possible. It does this without sacrificing speed where possible.
* [es](https://wryun.github.io/es-shell/) - (extensible shell) shell with first class functions, lexical scope, exceptions, and rich return values, based on Plan9's rc.
* [Fish](https://fishshell.com/) - "A command line shell for the 90s"; focused on user-friendliness, with powerful autosuggestions, colors, "sane scripting" (w\.r.t. to Bash).
* [mksh](http://www.mirbsd.org/mksh.htm) - (MirBSD Korn Shell) an actively developed free implementation of the Korn Shell programming language and a successor to the Public Domain Korn Shell (pdksh).
* [murex](https://murex.rocks) - An intuitive, typed and content aware shell for the 2020s and beyond.
* [PowerShell](https://microsoft.com/PowerShell) - An automation and configuration tool/framework optimized for dealing with structured data, REST APIs, and object models.
* [Rash](https://rash-lang.org) - A shell language, library, and REPL for Racket.
* [Tcsh](https://www.tcsh.org) - A shell that, at the time of creation, introduced command completion and command line editing.
* [xonsh](https://xon.sh/) - The xonsh shell lets you easily mix Python and shell commands in a powerful and simplified approach to the command line.
* [Yash](https://magicant.github.io/yash) - Yash (yet another shell) a POSIX-compliant command line shell written in C99.
* [Zsh](http://www.zsh.org/) - Alternative shell designed for interactive use.

## <a name="prompt"></a>Prompts

Prompts and welcome messages at the command line.

* [Powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 54,968 | 🐛 150 | 🌐 Shell | 📅 2026-08-15 - A theme for Zsh. It emphasizes speed, flexibility and out-of-the-box experience.
* [powerline](https://github.com/powerline/powerline) ⭐ 14,798 | 🐛 242 | 🌐 Python | 📅 2026-03-11 - Powerline is a statusline plugin for vim, and provides statuslines and prompts for several other applications, including zsh, bash, tmux, IPython, Awesome and Qtile.
* [Pure](https://github.com/sindresorhus/pure) ⭐ 14,400 | 🐛 0 | 🌐 Shell | 📅 2026-07-16 - Pretty, minimal, and fast ZSH prompt.
* [Liquid Prompt](https://github.com/liquidprompt/liquidprompt) ⭐ 4,674 | 🐛 30 | 🌐 Shell | 📅 2026-08-23 - Carefully designed prompt with useful information to show changes when it changes, saving time and frustration, and to show meaningful information with minimal visual clutter.
* [geometry](https://github.com/geometry-zsh/geometry) ⭐ 997 | 🐛 13 | 🌐 Shell | 📅 2025-01-13 - A minimalistic, fully customizable Zsh prompt theme with support for asynchronous functions.
* [Polyglot Prompt](https://github.com/agkozak/polyglot) ⭐ 195 | 🐛 5 | 🌐 Shell | 📅 2026-05-29 - A dynamic prompt for `zsh`, `bash`, `ksh93`, `mksh`, `pdksh`, `oksh`, `dash`, `yash`, `busybox ash`, and `osh` that uses basic ASCII symbols (and color, when possible).
* [welcome.sh](https://github.com/G2-Games/welcome.sh) ⭐ 64 | 🐛 1 | 🌐 Shell | 📅 2026-04-01 - A nice little script that greets you on every launch, with some helpful (and customizable!) information.
* [synth-shell-prompt](https://github.com/andresgongora/synth-shell-prompt) ⭐ 63 | 🐛 12 | 🌐 Shell | 📅 2026-08-22 - A small eye-candy shell prompt with Git status displaying, a clock, intelligent $PWD shortening, and much more.
* [blaze](https://github.com/danieltodor/blaze) ⭐ 43 | 🐛 0 | 🌐 C++ | 📅 2026-05-16 - A customizable and informative prompt for bash, zsh, fish, on linux distributions.
* [bashorg-motd](https://github.com/graydot/bashorg-motd) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2025-07-17 - More than 10 thousand quotes from the legendary bash\_org archives to see when you open a new terminal.
* [Basta!](https://www.kylheku.com/cgit/basta/about/) - A small amount of GNU Bash code that maintains a scroll-protected status line at the bottom of the terminal.
* [Oh My Posh](https://ohmyposh.dev) - From their README: "The most customizable and low-latency cross-platform/shell prompt renderer".
* [Spaceship](https://spaceship-prompt.sh/) - Minimalistic, powerful and extremely customizable Zsh prompt.
* [Starship](https://starship.rs/) - The cross-shell prompt for astronauts.

## <a name="copy-paste"></a>Copy/paste and clipboard

Clipboard managers and text copy/paste tools.

* [yank](https://github.com/mptre/yank) ⭐ 1,707 | 🐛 2 | 🌐 C | 📅 2026-07-16 - Reads input from stdin and display a selection interface that allows a field to be selected and copied to the clipboard.
* [extrakto](https://github.com/laktak/extrakto) ⭐ 1,138 | 🐛 1 | 🌐 Python | 📅 2026-03-02 - extrakto for tmux - quickly select, copy/insert/complete text without a mouse.
* [clipse](https://github.com/savedra1/clipse) ⭐ 1,029 | 🐛 44 | 🌐 Go | 📅 2026-06-09 - TUI-based clipboard manager application written in Go.
* [pcopy](https://github.com/binwiederhier/pcopy) ⭐ 423 | 🐛 15 | 🌐 Go | 📅 2024-04-04 - A temporary file host, nopaste and clipboard across machines. It can be used from the Web UI, via a CLI or without a client by using curl.
* [pbproxy](https://github.com/nikvdp/pbproxy) ⭐ 257 | 🐛 0 | 🌐 Shell | 📅 2022-12-30 - Send your clipboard anywhere you can ssh to.
* [shcopy](https://github.com/aymanbagabas/shcopy) ⭐ 86 | 🐛 0 | 🌐 Go | 📅 2026-08-15 - Copy text to your system clipboard locally and remotely using ANSI OSC52 sequence.
* [Clipsync](https://github.com/marcopaganini/clipsync) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2025-06-02 - Share your clipboard across multiple machines using an MQTT service.
* [copytools.sh](https://github.com/sdavidsson90/copytools.sh) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2025-04-26 - Tools for copying and pasting in the command line.
* [clipy](https://github.com/szktkfm/clipy) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2025-01-10 - Manage clipboard history.
* [clipboard-viewer](https://github.com/jaggzh/xclipview-tui) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-07-29 - Terminal-based clipboard browser.
* [clipper](https://github.com/supitsdu/clipper) - Seamlessly copy file contents to clipboard from command line. Lightweight, cross-platform tool for instant text transfers.

## <a name="monitor"></a>System monitoring

Applications to display the usage of system resources: network, memory, power, etc..

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 28,725 | 🐛 97 | 🌐 Rust | 📅 2026-04-30 - A command-line benchmarking tool.
* [Fastfetch](https://github.com/LinusDierheimer/fastfetch) ⭐ 24,356 | 🐛 77 | 🌐 C | 📅 2026-08-25 - Like Neofetch, but much faster because written in C.
* [fastfetch](https://github.com/fastfetch-cli/fastfetch) ⭐ 24,356 | 🐛 77 | 🌐 C | 📅 2026-08-25 - An actively maintained, feature-rich and performance oriented, neofetch like system information tool.
* [goaccess](https://github.com/allinurl/goaccess) ⭐ 20,837 | 🐛 457 | 🌐 C | 📅 2026-08-20 - GoAccess is a real-time web log analyzer and interactive viewer, that provides fast and valuable HTTP statistics.
* [WTF](https://github.com/senorprogrammer/wtf) ⭐ 17,061 | 🐛 102 | 🌐 Go | 📅 2026-08-05 - The personal information dashboard for your terminal.
* [TermUI](https://github.com/gizak/termui) ⭐ 13,580 | 🐛 106 | 🌐 Go | 📅 2025-07-10 - Cross-platform and fully-customizable TUI dashboard and widget library.
* [Cloud Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) ⭐ 8,653 | 🐛 36 | 🌐 Python | 📅 2026-07-05 - Real-time Claude Code usage monitor with predictions and warnings.
* [noti](https://github.com/variadico/noti) ⚠️ Archived - Monitor a process and trigger a notification.
* [screenFetch](https://github.com/KittyKatt/screenFetch) ⭐ 4,073 | 🐛 169 | 🌐 Shell | 📅 2026-03-02 - It can be used to generate one of those nifty terminal theme information + ASCII distribution logos. It auto-detects the distribution and display an ASCII version of that distribution's logo and some valuable information to the right.
* [kmon](https://github.com/orhun/kmon) ⭐ 2,937 | 🐛 23 | 🌐 Rust | 📅 2026-07-31 - Linux TUI Kernel manager and activity monitor.
* [CoreFreq](https://github.com/cyring/CoreFreq) ⭐ 2,239 | 🐛 1 | 🌐 C | 📅 2026-08-16 - CPU monitoring TUI software designed for the 64-bits Processors.
* [HyFetch](https://github.com/hykilpikonna/hyfetch) ⭐ 2,092 | 🐛 10 | 🌐 Shell | 📅 2026-08-09 - A fork of the abandoned [Neofetch](https://github.com/dylanaraps/neofetch) ⚠️ Archived, HyFetch displays information about your system next to an image, your OS logo, or any ASCII file of your choice.
* [macchina](https://github.com/Macchina-CLI/macchina) ⭐ 1,961 | 🐛 11 | 🌐 Rust | 📅 2025-03-08 - Fast, minimal and customizable system information frontend.
* [macmon](https://github.com/vladkens/macmon) ⭐ 1,828 | 🐛 14 | 🌐 Rust | 📅 2026-08-04 - Sudoless performance monitoring for Apple Silicon processors, including CPU, GPU, RAM usage, power consumption and temperature.
* [AdGuardian-Term](https://github.com/lissy93/AdGuardian-Term) ⭐ 1,640 | 🐛 13 | 🌐 Rust | 📅 2026-08-14 - A TUI dashboard for monitoring real-time traffic from an AdGuard Home instance.
* [Grafterm](https://github.com/slok/grafterm) ⭐ 1,138 | 🐛 11 | 🌐 Go | 📅 2022-06-10 - Metrics TUI dashboards on terminal, a Grafana inspired terminal version.
* [updo](https://github.com/Owloops/updo) ⭐ 1,122 | 🐛 6 | 🌐 Go | 📅 2026-05-26 - Uptime monitoring CLI tool with alerting and advanced settings.
* [otel-tui](https://github.com/ymtdzzz/otel-tui) ⭐ 1,069 | 🐛 31 | 🌐 Go | 📅 2026-08-24 - A terminal OpenTelemetry viewer, currently supporting OpenTelemetry, Zipkin (Traces) and Prometheus (Metrics) formats.
* [austin-tui](https://github.com/P403n1x87/austin-tui) ⭐ 665 | 🐛 2 | 🌐 Python | 📅 2026-06-04 - The top-like TUI user interface for Austin.
* [tcpterm](https://github.com/sachaos/tcpterm) ⭐ 488 | 🐛 0 | 🌐 Go | 📅 2024-01-10 - tcpterm is a packet visualizer in TUI.
* [slurm](https://github.com/mattthias/slurm) ⭐ 425 | 🐛 13 | 🌐 C | 📅 2024-02-04 - Yet another network load monitor.
* [zfxtop](https://github.com/ssleert/zfxtop) ⭐ 402 | 🐛 6 | 🌐 Go | 📅 2023-11-06 - Self described as “fetch top written by bubbletea enjoyer”.
* [tdash](https://github.com/jessfraz/tdash) ⭐ 321 | 🐛 1 | 🌐 Go | 📅 2023-02-24 - A terminal dashboard with stats from Google Analytics, GitHub, Travis CI, and Jenkins. Very much built specific to the author of the tool.
* [chdig](https://github.com/azat/chdig) ⭐ 292 | 🐛 5 | 🌐 Rust | 📅 2026-08-24 - Dig into ClickHouse with TUI interface.
* [amtui](https://github.com/pehlicd/amtui/) ⭐ 113 | 🐛 4 | 🌐 Go | 📅 2026-06-20 - A terminal-based user interface (TUI) application that allows you to interact with Prometheus Alertmanager using your terminal. It provides a convenient way to monitor alerts, view silences, and check the status of Alertmanager instances.
* [act3](https://github.com/dhth/act3) ⭐ 80 | 🐛 4 | 🌐 Go | 📅 2026-06-07 - Glance at the last 3 runs of your Github Actions.
* [llmtop](https://github.com/arinbjornk/llmtop) ⭐ 67 | 🐛 3 | 🌐 Python | 📅 2025-12-23 - A system monitoring tool powered by LLMs that provides real-time insights about your system's performance.
* [tmd-top](https://github.com/CDWEN0526/tmd-top) ⭐ 60 | 🐛 1 | 🌐 Python | 📅 2024-12-24 - Used to monitor the process TCP traffic of the Linux system, detailed to each IP connection.
* [tmon](https://github.com/pondda/tmon) ⭐ 29 | 🐛 1 | 🌐 C++ | 📅 2024-12-14 - A tiny system monitor for Linux.
* [tuihub](https://github.com/ashis0013/tuihub) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2023-09-22 - TUI to manage todos and getting handy information on machine usage and time.
* [Batfetch](https://github.com/ashish-kus/batfetch) ⭐ 24 | 🐛 7 | 🌐 Shell | 📅 2024-08-08 - A command-line tool that displays detailed information about the battery of your device in a clean and organized way.
* [ptrstream](https://github.com/acidvegas/ptrstream) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2025-01-20 - High-performance distributed PTR record scanner with real-time streaming output.
* [nitchplusplus](https://github.com/clamsfeel2/nitchplusplus) ⭐ 13 | 🐛 0 | 🌐 C++ | 📅 2026-03-08 - A fast system information fetch tool.
* [ramfetch](https://github.com/WhoseTheNerd/ramfetch) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2024-01-20 - A fetch which displays memory info using /proc/meminfo.
* [plox](https://github.com/michalkucharczyk/plox) ⭐ 5 | 🐛 0 | 🌐 HTML | 📅 2026-01-06 - Extract numeric values from log files and plot them over time. Fully CLI-driven.
* [senzu](https://github.com/Hakky54/senzu) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2026-07-27 - CLI tool to get the battery percentage.
* [aserial](https://github.com/CT3/aserial) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2024-12-31 - A serial monitor with error/warning highlighting and scrollable interface.
* [Bashmark](https://github.com/Samrat079/Bashmark) ⭐ 2 | 🐛 0 | 🌐 Makefile | 📅 2025-06-12 - Terminal based benchmarking utility for testing CPU and GPU performance.
* [dmidecode](https://www.nongnu.org/dmidecode/) - System information utility.
* [dysk](https://dystroy.org/dysk) - A thing to get information on your mounted disks
* [GFetch](https://github.com/tanaybhomia/GFetch) - A simple fetch script written in Python.
* [glances](https://nicolargo.github.io/glances/) - A comprehensive and detailed system monitor; monitored parameters include: CPU, memory, load, process list, network interfaces, disk I/O, sensors, filesystems, docker, system info, uptime.
* [inxi](http://smxi.org/docs/inxi.htm) - A comprehensive system information script; provides information about CPU, graphics, audio and network devices, drives and partitions, sensors; implemented as a Bash script.
* [multitail](https://www.vanheusden.com/multitail/) - Open multiple log files in a single terminal window and monitor them in real-time.
* [ngrep](http://ngrep.sourceforge.net/) - (Network grep) applies the `grep` logic to the network layer, allowing to match regular expressions against data payloads of packets; it recognizes IPv4/6, TCP, UDP, ICMPv4/6, IGMP and Raw across Ethernet, PPP, SLIP, FDDI, Token Ring and null interfaces.
* [powertop](https://01.org/powertop) - A `top`-like utility to monitor the sources of power consumption, allows turning on/off many components, quite useful to track possible power-related issues.
* [pv](http://www.ivarch.com/programs/pv.shtml) - The pv command is used to monitor the progress of data through pipe.
* [smem](https://www.selenic.com/smem/) - Python program that reports memory usage; it can report the "proportional set size" (PSS), a meaningful representation of the amount of memory used by libraries and applications in a virtual memory system; it has built-in chart generation.
* [sntop](https://sourceforge.net/projects/sntop) - A simple network top for monitoring connectivity.
* [sysdig](https://www.sysdig.org/) - A TUI for capturing system calls and events from the Linux kernel. Allows you to save, filter, and analyze the data. Like `strace` + `tcpdump` + `htop` + `iftop` + `lsof` + Wireshark for the entire system.
* [The Logfile Navigator](https://lnav.org/) - An advanced and colorful log file viewer with TUI interface.
* [tinyfetch](https://github.com/beucismis/tinyfetch) - Python and system information command-line fetch tool.
* [ttyload](http://www.daveltd.com/src/util/ttyload/) - Lightweight utility that offers a color-coded graph of load averages over time, enabling a graphical tracking of system average load.
* [whowatch](https://www.tecmint.com/whowatch-monitor-linux-users-and-processes-in-real-time/) - Monitor Linux Users and Processes in Real Time.

# <a name="Environment-Management-Tools"></a>Environment Management Tools

## <a name="package-manager"></a>Package managers

Package managers to manage/install/uninstall software packages, as source code or binaries.

* [topgrade](https://github.com/topgrade-rs/topgrade) ⭐ 4,433 | 🐛 211 | 🌐 Rust | 📅 2026-08-24 - Upgrade all the things.
* [eget](https://github.com/zyedidia/eget) ⭐ 2,059 | 🐛 57 | 🌐 Go | 📅 2024-07-09 - Easily install prebuilt binaries from GitHub.
* [bin](https://github.com/marcosnils/bin) ⭐ 1,269 | 🐛 91 | 🌐 Go | 📅 2026-08-02 - Manages binary files downloaded from different sources.
* [upt](https://github.com/sigoden/upt) ⭐ 527 | 🐛 3 | 🌐 Rust | 📅 2024-10-31 - Universal Package-management Tool for any OS.
* [stew](https://github.com/marwanhawari/stew) ⭐ 353 | 🐛 24 | 🌐 Go | 📅 2025-05-06 - An independent package manager for compiled binaries.
* [Shell Bling Ubuntu](https://github.com/hiAndrewQuinn/shell-bling-ubuntu) ⭐ 231 | 🐛 5 | 🌐 Shell | 📅 2026-08-17 - A few scripts to be run on a fresh-off-the-presses Ubuntu VM, in order to get its shell nice 'n purdy.
* [app](https://github.com/hkdb/app) ⭐ 176 | 🐛 3 | 🌐 Go | 📅 2026-04-15 - A cross-platform package management assistant with super powers.
* [TUI-SHOP](https://github.com/Gcat101/tui-shop) ⭐ 72 | 🐛 1 | 🌐 Python | 📅 2022-07-10 - TUI-SHOP allows you to browse and install apps directly
* [ToolUI](https://github.com/jinek/ToolUI) ⭐ 67 | 🐛 2 | 🌐 C# | 📅 2022-10-29 - TUI to manage dotnet tools.
* [pkm](https://github.com/wick3dr0se/pkm) ⭐ 64 | 🐛 1 | 🌐 Shell | 📅 2024-06-17 - A super minimal TUI package manager wrapper written in BASH v4-2+.
* [pypi-command-line](https://github.com/wasi-master/pypi-command-line) ⭐ 53 | 🐛 1 | 🌐 Python | 📅 2026-07-18 - A powerful, colorful, beautiful command-line-interface for pypi.org.
* [cli-tools-info](https://github.com/Lilja/cli-info) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2022-11-19 - An overview of your CLI tools, if they are installed and what version they are on.
* [getghrel](https://github.com/kavishgr/getghrel) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2026-01-10 - A user-friendly command-line tool that fetches and installs the latest release assets from GitHub for macOS and Linux; it automatically detects your operating system and architecture, downloads the relevant binary, and unpacks it, ensuring a hassle-free experience.
* [flatpak-cli](https://github.com/sweetbbak/flatpak-cli) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2024-01-27 - A command line program to search and install flatpaks from the flathub repository using a fzf like interface.
* [JAPM](https://github.com/TheAlexDev23/japm) ⭐ 12 | 🐛 0 | 🌐 C | 📅 2023-05-17 - A package manager that uses curses to provide a friendly UI
* [autoupd](https://github.com/2SSK/autoupd) ⭐ 7 | 🐛 1 | 🌐 Go | 📅 2025-07-21 - A simple CLI too to automatically update system packages using your Linux distro's package manager, with daily logs and systemd integration.
* [pmt](https://github.com/olexij-christian/pmt) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-05-04 - Translator of package names between different package managers of Linux distributions.
* [pm-jesus](https://github.com/sebastiancarlos/pm-jesus) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2024-04-29 - Package manager front-end.
* [aptitude](https://salsa.debian.org/apt-team/aptitude) - A TUI front-end to APT, the Debian package manager.
* [asdf](https://asdf-vm.com/) - Manage multiple runtime versions with a single CLI tool.
* [godyl](https://idelchi.github.io/godyl/) - Helps with batch-downloading, checksum verifying and installing statically compiled binaries from GitHub, GitLab, URLs, Go projects.
* [krew](https://krew.sigs.k8s.io/) - Find and install kubectl plugins.
* [lastversion](https://lastversion.getpagespeed.com) - Find the latest stable version and download assets of any project from GitHub, GitLab, PyPI, and other sources.
* [mise](https://mise.jdx.dev/) - A development environment setup tool: dev tools, env vars, and task runner. Like `asdf` + `direnv` + `make`.
* [nala](https://gitlab.com/volian/nala) - apt package manager front-end with cleaner interface.

## <a name="vm"></a>Containerization and virtualization

Tools to manage virtual machines and/or containers and related utilities.

* [dive](https://github.com/wagoodman/dive) ⭐ 54,488 | 🐛 211 | 🌐 Go | 📅 2025-12-15 - A tool for exploring each layer in a docker image.
* [lazydocker](https://github.com/jesseduffield/lazydocker) ⭐ 52,598 | 🐛 295 | 🌐 Go | 📅 2026-04-19 - The lazier way to manage everything docker. A simple terminal UI for both docker and docker-compose, written in Go with the gocui library.
* [ctop](https://github.com/bcicen/ctop) ⭐ 17,825 | 🐛 121 | 🌐 Go | 📅 2024-07-08 - Top-like interface for container metrics.
* [quickemu](https://github.com/quickemu-project/quickemu) ⭐ 15,712 | 🐛 68 | 🌐 Shell | 📅 2026-08-14 - Quickly create and run optimized Windows, macOS and Linux desktop virtual machines.
* [distrobox](https://github.com/89luca89/distrobox) ⭐ 12,900 | 🐛 143 | 🌐 Go | 📅 2026-08-21 - Use any Linux distribution inside your terminal as docker or podman containers.
* [bocker](https://github.com/p8952/bocker) ⭐ 12,666 | 🐛 15 | 🌐 Shell | 📅 2017-12-09 - Docker implemented in around 100 lines of bash.
* [Dockly](https://github.com/lirantal/dockly) ⭐ 4,032 | 🐛 5 | 🌐 JavaScript | 📅 2026-07-23 - Immersive terminal interface for managing docker containers, services, and images.
* [dry](https://github.com/moncho/dry) ⭐ 3,266 | 🐛 27 | 🌐 Go | 📅 2026-08-21 - A Docker manager for the terminal.
* [ContainerSSH](https://github.com/ContainerSSH/ContainerSSH) ⭐ 3,073 | 🐛 59 | 🌐 Go | 📅 2026-08-21 - An SSH Server that Launches Containers in Kubernetes and Docker on demand.
* [oxker](https://github.com/mrjackwills/oxker) ⭐ 1,819 | 🐛 23 | 🌐 Rust | 📅 2026-08-22 - A simple TUI to view & control docker containers.
* [nemu](https://github.com/nemuTUI/nemu) ⭐ 598 | 🐛 16 | 🌐 C | 📅 2026-06-11 - Ncurses UI for QEMU.
* [EMU2](https://github.com/dmsc/emu2) ⭐ 463 | 🐛 25 | 🌐 C | 📅 2026-07-04 - A simple DOS emulator for the Linux text console, supporting basic DOS system calls and console I/O.
* [docker-shell](https://github.com/Trendyol/docker-shell) ⚠️ Archived - A simple interactive prompt for Docker.
* [Pocker](https://github.com/pommee/Pocker) ⭐ 188 | 🐛 2 | 🌐 Python | 📅 2025-03-16 - Pocker is a TUI tool to help with docker related tasks, such as view containers/images, manage status of containers, see logs, attributes, environment variables and container statistics, filter logs based on keywords, start shell inside a container.
* [decompose](https://github.com/s0rg/decompose) ⭐ 141 | 🐛 7 | 🌐 Go | 📅 2026-07-31 - Reverse-engineering tool for docker environments.
* [VCTUI](https://github.com/thebsdbox/vctui) ⭐ 38 | 🐛 2 | 🌐 Go | 📅 2020-05-14 - Console interface for vCenter: create, delete and search virtual machines and power management.
* [ocui](https://github.com/fishinthecalculator/ocui) ⭐ 11 | 🐛 10 | 🌐 Python | 📅 2025-11-18 - Simple text based UI for managing containers.
* [docker](https://docs.docker.com/) - Self-sufficient runtime for containers.
* [Incus](https://linuxcontainers.org/lxc) - A manager/hypervisor for containers (via LXC) and virtual-machines (via QEMU).
* [lxc](https://linuxcontainers.org/lxc) - A userspace interface for the Linux kernel containment features.
* [podman](https://podman.io/) - Podman is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using OCI Containers and Container Images.
* [QEMU](https://qemu.org) - A generic machine & userspace emulator and virtualizer.
* [toolbox](https://containertoolbx.org) - Use containerized environments where development tools and libraries can be easily installed and used.
* [virsh](https://libvirt.org/index.html) - An interactive shell, and batch scriptable tool for performing management tasks on all libvirt managed domains, networks, and storage. A part of the libvirt core distribution.
* [Waydroid](https://waydro.id) - A container-based approach to boot a full Android system on a regular Linux distribution.

## <a name="launcher"></a>Command launchers

Applications to launch/execute programs, either interactively, automatically, in parallel, etc..

* [rofi](https://github.com/davatorium/rofi) ⭐ 16,353 | 🐛 117 | 🌐 C | 📅 2026-08-09 - A window switcher, application launcher and dmenu replacement.
* [pueue](https://github.com/Nukesor/pueue) ⭐ 6,300 | 🐛 20 | 🌐 Rust | 📅 2026-08-16 - Pueue is a command-line task management tool for sequential and parallel execution of long-running tasks.
* [entr](https://github.com/eradman/entr) ⭐ 5,656 | 🐛 1 | 🌐 C | 📅 2026-06-27 - Event Notify Test Runner - Run an arbitrary command when files change.
* [process-compose](https://github.com/F1bonacc1/process-compose) ⭐ 2,715 | 🐛 16 | 🌐 Go | 📅 2026-08-17 - TUI for running apps and processes.
* [mprocs](https://github.com/pvolok/mprocs) ⭐ 2,701 | 🐛 67 | 🌐 Rust | 📅 2026-08-24 - mprocs runs multiple commands in parallel and shows output of each command separately.
* [Marker](https://github.com/pindexis/marker) ⭐ 2,092 | 🐛 49 | 🌐 Python | 📅 2024-04-06 - The terminal command palette.
* [shell2http](https://github.com/msoap/shell2http) ⭐ 1,503 | 🐛 6 | 🌐 Go | 📅 2026-08-08 - Executing shell commands via HTTP server.
* [Steam TUI](https://github.com/dmadisetti/steam-tui) ⭐ 1,033 | 🐛 9 | 🌐 Rust | 📅 2026-03-12 - A simple TUI client for steamcmd, allows for the graphical launching, updating, and downloading of steam games through a simple terminal client.
* [sake](https://github.com/alajmo/sake) ⭐ 750 | 🐛 16 | 🌐 Go | 📅 2026-05-31 - A command runner for local and remote hosts. You define servers and tasks in sake.yaml file and then run the tasks on the servers.
* [sunbeam](https://github.com/pomdtr/sunbeam) ⭐ 553 | 🐛 10 | 🌐 Go | 📅 2025-05-30 - General purpose command-line launcher that defines UIs composed of a succession of views from simple scripts written in any language; a mix between an application launcher like `raycast` or `rofi` and a fuzzy-finder like `fzf` or `telescope`.
* [Gaze](https://github.com/wtetsu/gaze) ⭐ 314 | 🐛 2 | 🌐 Go | 📅 2026-07-13 - Runs a command, right after you save a file.
* [foy](https://github.com/zaaack/foy) ⭐ 290 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-12 - A simple, light-weight, type-friendly and modern task runner for general purpose.
* [hypershell](https://github.com/holepunchto/hypershell) ⭐ 253 | 🐛 5 | 🌐 JavaScript | 📅 2024-03-18 - Spawn shells anywhere. Fully peer-to-peer, authenticated, and end-to-end encrypted.
* [procmux](https://github.com/napisani/procmux) ⭐ 111 | 🐛 2 | 🌐 Python | 📅 2025-11-23 - A TUI utility for running multiple commands in parallel in easily switchable terminals.
* [lmt](https://github.com/Rohansjamadagni/lmt) ⭐ 87 | 🐛 1 | 🌐 Go | 📅 2025-02-04 - A program that can be used to run applications with resource limits enforced using cgroupsv2 on Linux; it allows setting limits on CPU usage, memory usage, and the number of cores for a process.
* [mk](https://github.com/orangekame3/mk) ⭐ 52 | 🐛 0 | 🌐 Go | 📅 2024-10-28 - Interactive task runner for Makefile or Taskfile.yml, designed to interactively execute make commands. It provides a user-friendly interface to select and run predefined commands, making it easier to manage and execute build tasks.
* [paneru](https://github.com/pondda/paneru) ⭐ 40 | 🐛 0 | 🌐 C++ | 📅 2025-10-01 - Launcher panel from the terminal.
* [climenu](https://github.com/10xJSChad/climenu) ⭐ 39 | 🐛 0 | 🌐 C | 📅 2025-11-10 - Compact application for creating shell menus with executable entries. Use it to build straightforward static shortcut menus or dynamically generate advanced menus for more complex programs.
* [mash](https://github.com/dennisbergevin/mash) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2025-07-17 - A customizable command launcher for storing and executing commands with a tree view of commands and filterable list tagging.
* [menu.sh](https://github.com/iandennismiller/menu.sh) ⭐ 32 | 🐛 0 | 🌐 Shell | 📅 2025-04-07 - A lightweight menu and launcher for text-mode consoles. Menus are described with YAML and sub-menus are supported.
* [Violet](https://github.com/braheezy/violet) ⭐ 31 | 🐛 4 | 🌐 Go | 📅 2026-02-16 - Colorful TUI frontend to run Vagrant commands.
* [Sway-Talisman](https://github.com/sebastiancarlos/sway-talisman) ⚠️ Archived - Terminal application launcher in scratchpad, minimalist and native.
* [taverner](https://github.com/vagos/taverner) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2025-05-26 - CLI launcher menu for games (or anything), the UNIX way.
* [Mxflow-cli](https://github.com/metaory/mxflow-cli) ⭐ 12 | 🐛 5 | 🌐 JavaScript | 📅 2025-11-10 - A modern, general purpose CLI task runner with human-readable YAML config file.
* [fzs](https://github.com/Squirreljetpack/fzs) - "Fuzzy selector for your binaries that generalizes the function of launchers like rofi and alfred/raycast using the concept of plugins to group related "actions".
* [parallel](https://www.gnu.org/software/parallel/) - A shell tool from GNU for executing jobs in parallel using one or more computers, it can split the input and pipe it into commands in parallel.
* [Task](https://taskfile.dev/) - A task runner / simpler Make alternative written in Go.
* [task-spooler](http://vicerveza.homeunix.net/~viric/soft/ts/) - A Unix batch system that can be used to add the Linux commands to the queue and execute them one after the other in numerical order (ascending order, to be precise). This can be very useful when you have to run a lot of commands, but you don't want to waste time waiting for one command to finish and run the next command. You can queue it all up and Task Spooler will execute them one by one. In the mean time, you can do other activities.

## <a name="dotfiles"></a>Dotfile managers

Tools to handle, backup and share system dotfiles.

* [dotbins](https://github.com/basnijholt/dotbins) ⭐ 271 | 🐛 28 | 🌐 Python | 📅 2026-08-14 - Keep updated binaries in your dotfiles.
* [YAS-BDSM](https://github.com/sebastiancarlos/yas-bdsm) ⭐ 60 | 🐛 0 | 🌐 Shell | 📅 2023-11-10 - YAS-BDSM (Yet Another Stow-Based Dotfiles System Manager): a minimal, UNIX-based, cross-platform, hierarchical dotfiles manager.
* [ydf](https://github.com/yunielrc/ydf) ⭐ 28 | 🐛 11 | 🌐 Shell | 📅 2025-01-24 - A disruptive dotfiles manager+. Be ready to work in just a few minutes on your Fresh OS.
* [fyora](https://github.com/wenbang24/fyora) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2025-09-21 - Intuitive declarative dotfile management.
* [chezmoi](https://www.chezmoi.io/) - Manage your dotfiles across multiple diverse machines, securely.

## <a name="font"></a>Font management

Utilities to manage system fonts and to generate text using ASCII-art-like characters.

* [cfonts](https://github.com/dominikwilkowski/cfonts) ⭐ 1,887 | 🐛 3 | 🌐 Rust | 📅 2026-08-23 - А command line tool for generating ANSI fonts in the console.
* [fnt](https://github.com/alexmyczko/fnt) ⭐ 637 | 🐛 9 | 🌐 Shell | 📅 2026-08-14 - apt for fonts, the missing font manager for macOS/Linux.
* [Iconic Fonts](https://github.com/iconicFonts/iconic-fonts) ⚠️ Archived - A collection of over 50 patched fonts featuring over 60,000 icons, tailored specifically for TUIs.
* [FIGlet](http://www.figlet.org/) - Not exactly a font manager, but a nice program for making large letters out of ordinary text; an astonishing number of different fonts is available.
* [toilet](http://caca.zoy.org/wiki/toilet) - Tries to improve `FIGlet`; can load FIGlet fonts; supports Unicode input and output, color fonts and output, and various output formats, including HTML, IRC and ANSI; uses `libcaca` to produce nice textual effects.

# <a name="Communication-and-Networking"></a>Communication and Networking

## <a name="email"></a>Email

Email clients (MUA - Mail User Agents), mail synchronization, generation indexing and search.

* [Himalaya](https://github.com/soywod/himalaya) ⭐ 7,099 | 🐛 5 | 🌐 Rust | 📅 2026-08-24 - Command-line interface for email management.
* [Himalaya](https://github.com/pimalaya/himalaya) ⭐ 7,099 | 🐛 5 | 🌐 Rust | 📅 2026-08-24 - CLI to manage emails.
* [tmpmail](https://github.com/sdushantha/tmpmail) ⭐ 4,188 | 🐛 7 | 🌐 Shell | 📅 2024-08-17 - A command line utility written in POSIX sh that allows you to create a temporary email address and receive emails to the temporary email address.
* [pop](https://github.com/charmbracelet/pop) ⭐ 2,902 | 🐛 29 | 🌐 Go | 📅 2026-08-20 - Send emails from your terminal; it uses the API at [https://resend.com/](resend.com).
* [Open Archiver](https://github.com/LogicLabs-OU/OpenArchiver) ⭐ 2,276 | 🐛 208 | 🌐 TypeScript | 📅 2026-08-24 - The program provides a solution for archiving, storing, indexing and searching emails from major platforms.
* [meli](https://github.com/meli/meli) ⭐ 886 | 🐛 9 | 🌐 Rust | 📅 2026-08-24 - Terminal mail client.
* [alot](https://github.com/pazz/alot) ⭐ 748 | 🐛 225 | 🌐 Python | 📅 2026-07-29 - MUA written in Python using the [NotMuch](https://notmuchmail.org/) backend, MailDir format support.
* [mailsy](https://github.com/BalliAsghar/Mailsy.git) ⭐ 597 | 🐛 1 | 🌐 JavaScript | 📅 2024-12-03 - Generates disposable emails in the CLI through [mail.tm](https://mail.tm).
* [gmailtail](https://github.com/c4pt0r/gmailtail) ⭐ 445 | 🐛 1 | 🌐 Python | 📅 2026-05-28 - Command-line tool to monitor Gmail messages and output the as JSON; The program in designed for automation, monitoring and integration with other tools.
* [nmail](https://github.com/d99kris/nmail) ⭐ 255 | 🐛 0 | 🌐 C++ | 📅 2026-08-15 - nmail is a console-based email client for Linux and macOS with a user interface similar to alpine / pine.
* [maildir-rank-addr](https://github.com/ferdinandyb/maildir-rank-addr) ⭐ 43 | 🐛 3 | 🌐 Go | 📅 2025-11-14 - Creates a ranked list of email addresses from local email files, which can be used for address completion for example in aerc.
* [paws](https://github.com/tomhrr/paws) ⭐ 8 | 🐛 0 | 🌐 Perl | 📅 2024-05-18 - sendmail/maildir interface to Slack.
* [pymailgen](https://github.com/toolleeo/pymailgen) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-11-04 - Starting from the content of a CSV file and a template text file, pymailgen generates a list of emails to be sent out using a command-line SMTP client.
* [Mailtide](https://github.com/LandonH2007/mailtide) ⭐ 1 | 🐛 0 | 📅 2025-07-14 - Lightweight Python-based CLI email client that allows you to browse and manage IMAP inboxes via terminal and send emails.
* [abook](https://abook.sourceforge.io/) - TUI addressbook with Mutt mail client integration (runs on Linux, FreeBSD and other UNIXes).
* [aerc](https://aerc-mail.org/) - A pretty good email client
* [alpine](http://www.washington.edu/alpine/) - Mail client which aims at being "fast, easy to use email client that is suitable for both the inexperienced email user as well as for the most demanding of power users".
* [mbsync](http://isync.sourceforge.net/mbsync.html) - Mailboxes synchronization tool, allows downloading email locally, MailDir format supported.
* [Mutt](http://www.mutt.org/) - Mail client with tons of features, customization chances, support for IMAP, POP3, multiple storage formats.
* [NeoMutt](https://neomutt.org/) - Patched and up-to-dated mutt fork.
* [Notmuch](https://git.notmuchmail.org/git/notmuch) - Notmuch is a command-line based program for indexing, searching, reading, and tagging large collections of email messages.
* [quackalias-cli](https://github.com/Megane0103/quackalias-cli) - Scripts to generate DuckDuckGo email aliases and store the history of generated aliases.
* [sup](http://sup-heliotrope.github.io/) - MUA written in Ruby; specifically developed for accounts with "a lot of emails"; nice thread-based presentation.

## <a name="chat"></a>Chat and instant messaging

Clients for chat and other instant messaging protocols, e.g., IRC, Discord, Mattermost, Matrix, Slack, Telegram, Reddit.

* [Telegram messenger CLI](https://github.com/vysheng/tg) ⭐ 7,165 | 🐛 1,188 | 🌐 C | 📅 2024-04-23 - Command-line interface for Telegram using the readline interface.
* [slack-term](https://github.com/erroneousboat/slack-term) ⭐ 6,611 | 🐛 68 | 🌐 Go | 📅 2024-04-23 - Slack client for the  terminal.
* [ssh-chat](https://github.com/shazow/ssh-chat) ⭐ 5,909 | 🐛 54 | 🌐 Go | 📅 2026-01-10 - Custom SSH server written in Go. Instead of a shell, you get a chat prompt.
* [Discordo](https://github.com/ayn2op/discordo) ⭐ 5,739 | 🐛 56 | 🌐 Go | 📅 2026-08-22 - A lightweight, secure, and feature-rich Discord terminal client.
* [signal-cli](https://github.com/AsamK/signal-cli) ⭐ 4,883 | 🐛 106 | 🌐 Java | 📅 2026-08-21 - signal-cli provides an unofficial command-line, dbus and JSON-RPC interface for the Signal messenger.
* [devzat](https://github.com/quackduck/devzat) ⭐ 4,065 | 🐛 26 | 🌐 Go | 📅 2026-07-23 - Custom SSH server that takes you to a chat instead of a shell prompt.
* [Sclack](https://github.com/haskellcamargo/sclack) ⭐ 2,478 | 🐛 44 | 🌐 Python | 📅 2022-12-08 - CLI client for Slack.
* [Instagram CLI](https://github.com/supreme-gg-gg/instagram-cli) ⭐ 2,124 | 🐛 40 | 🌐 TypeScript | 📅 2026-08-22 - Instagram from your terminal; It allows you to use social media more intentionally (chat, stay updated with post and stories without falling into endless brainrot).
* [nchat](https://github.com/d99kris/nchat) ⭐ 1,927 | 🐛 16 | 🌐 C++ | 📅 2026-08-23 - Terminal Telegram, WhatsApp and Signal client for LInux and macOS.
* [gomuks](https://github.com/tulir/gomuks) ⭐ 1,717 | 🐛 73 | 🌐 Go | 📅 2026-08-23 - A terminal based Matrix client written in Go.
* [gurk](https://github.com/boxdot/gurk-rs) ⭐ 1,364 | 🐛 100 | 🌐 Rust | 📅 2026-07-29 - Signal Messenger client for terminal.
* [toot](https://github.com/ihabunek/toot) ⭐ 1,320 | 🐛 127 | 🌐 Python | 📅 2026-07-04 - Mastodon CLI & TUI.
* [toxic](https://github.com/Jfreegman/toxic) ⭐ 1,303 | 🐛 19 | 🌐 C | 📅 2026-07-14 - A Tox-based instant messaging and video chat client.
* [tiny](https://github.com/osa1/tiny) ⭐ 1,179 | 🐛 94 | 🌐 Rust | 📅 2026-03-19 - tiny is an IRC client written in Rust.
* [matterhorn](https://github.com/matterhorn-chat/matterhorn) ⭐ 1,152 | 🐛 22 | 🌐 Haskell | 📅 2026-08-19 - A terminal client for the Mattermost chat system.
* [tgt](https://github.com/FedericoBruzzone/tgt) ⭐ 997 | 🐛 15 | 🌐 Rust | 📅 2026-08-17 - A TUI for Telegram written in Rust.
* [Weechat-Matrix](https://github.com/poljar/weechat-matrix) ⭐ 993 | 🐛 127 | 🌐 Python | 📅 2023-07-23 - A Python script for Weechat that lets Weechat communicate over the Matrix protocol.
* [Endcord](https://github.com/mzivic7/endcord) ⭐ 963 | 🐛 3 | 🌐 Python | 📅 2026-08-24 - Lightweight and feature rich Discord TUI client, running entirely in terminal, built with python and ncurses library.
* [PingMe](https://github.com/kha7iq/pingme) ⭐ 863 | 🐛 4 | 🌐 Go | 📅 2026-07-15 - Sends messages or alerts to multiple messaging platforms & email, including Slack, Telegram, Mattermost, WeChat, and others.
* [Zulip Terminal](https://github.com/zulip/zulip-terminal) ⭐ 857 | 🐛 474 | 🌐 Python | 📅 2026-08-16 - Official Zulip terminal client with TUI.
* [tweets](https://github.com/diracdeltas/tweets) ⭐ 777 | 🐛 8 | 🌐 Shell | 📅 2024-04-06 - Decentralized alternative to Twitter that uses git as support tool to manage the tweets.
* [matrix-commander](https://github.com/8go/matrix-commander) ⭐ 752 | 🐛 36 | 🌐 Python | 📅 2026-07-23 - Simple but convenient CLI-based Matrix client app for sending and receiving.
* [twitch-tui](https://github.com/Xithrius/twitch-tui) ⭐ 632 | 🐛 10 | 🌐 Rust | 📅 2026-05-29 - Twitch chat in the terminal.
* [scli](https://github.com/isamert/scli) ⭐ 537 | 🐛 26 | 🌐 Python | 📅 2024-11-30 - A simple terminal user interface for signal messenger.
* [tut](https://github.com/RasmusLindroth/tut) ⭐ 500 | 🐛 56 | 🌐 Go | 📅 2023-12-18 - TUI for Mastodon with vim inspired keys.
* [siggo](https://github.com/derricw/siggo) ⚠️ Archived - TUI for signal-cli, written in Go, vim-style ux (quick messages, emoji support, configurable contacts, filter messages).
* [ZUSE](https://github.com/babycommando/zuse) ⭐ 322 | 🐛 1 | 🌐 Go | 📅 2025-07-28 - Minimal IRC client for the terminal written in Go with Bubbletea.
* [twterm](https://github.com/ryota-ka/twterm) ⭐ 245 | 🐛 23 | 🌐 Ruby | 📅 2023-12-15 - A full-featured TUI Twitter client.
* [tuisky](https://github.com/sugyan/tuisky) ⭐ 163 | 🐛 11 | 🌐 Rust | 📅 2025-12-28 - TUI client for Bluesky.
* [matrixcli](https://github.com/saadjsct/matrixcli) ⭐ 139 | 🐛 17 | 🌐 Python | 📅 2024-04-21 - A minimal command line matrix client.
* [Gomphotherium](https://github.com/mrusme/gomphotherium) ⚠️ Archived - A command line Mastodon client, offering a CLI and TUI with usage similar to rainbowstream; Intended to be used at 80 characters width maximum, ideally inside tmux as a sidebar-style program.
* [Servitor](https://github.com/bentonedmondson/servitor) ⭐ 83 | 🐛 2 | 🌐 Go | 📅 2024-07-22 - A command-line Fediverse client that doesn’t require a server.
* [icy\_tools](https://github.com/mkrueger/icy_term) ⚠️ Archived - Icy Term a terminal program for legacy BBS systems, Icy Draw a drawing tool supporting almost all ANSI formats, Icy View a viewer to browse/view Ansi screens, Icy Play a tool that shows icy draw animations on cmd line/bbs.
* [nostui](https://github.com/akiomik/nostui) ⭐ 68 | 🐛 6 | 🌐 Rust | 📅 2026-08-24 - TUI client for Nostr.
* [ttchat](https://github.com/atye/ttchat) ⭐ 61 | 🐛 10 | 🌐 Go | 📅 2025-01-06 - Twitch chats in the terminal.
* [tgbounce](https://github.com/azhuchkov/tgbounce) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2024-05-09 - Simple Telegram Assistant that allows replying to messages, clicking buttons from bots, marking messages as read, logging notable messages, and providing desktop notifications, among other features.
* [cli\_chat\_app](https://github.com/Johnkhk/cli_chat_app) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2025-02-27 - A end-to-end encrypted chat application.
* [nostratui](https://github.com/adamm-xyz/nostratui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2025-06-10 - TUI for browsing Nostr posts, written in Rust.
* [finch](http://www.pidgin.im/) - IM program supporting many protocols, including Yahoo!, AIM, IRC, or WLM; comes with the `Pidgin` project.
* [GNU Freetalk](https://www.gnu.org/software/freetalk/) - A console based chat client for Jabber and other XMPP servers. It has context-sensitive autocompletion for buddy names, commands, and even ordinary English words.
* [iamb](https://iamb.chat/) - A Matrix client for the terminal that uses Vim keybindings.
* [irssi](http://www.irssi.org) - The most popular IRC client for the command-line; a flexible program, with many options and supporting many protocols.
* [kirc](http://kirc.io/) - A tiny IRC client written in POSIX C99.
* [MCABBER](https://mcabber.com/) - A small XMPP (Jabber) console client including features such as SASL/SSL/TLS support, MUC (Multi-User Chat) support, history logging, command completion, OpenPGP encryption and more.
* [Poezio](https://poez.io/en/) - Poezio is a free console XMPP client. It lets you connect very easily (no account creation needed) to the network and join various chatrooms. Many commands are identical to common IRC clients. Configuration can be made in a configuration file or directly from the client.
* [Profanity](https://profanity-im.github.io/) - Profanity is a console based XMPP client written in C using ncurses and libstrophe, inspired by Irssi.
* [RainbowStream](http://www.rainbowstream.org/) - Twitter client for the terminal allows almost all the operations that can be done from GUI and Web clients.
* [senpai](https://git.sr.ht/~delthas/senpai/) - A modern terminal IRC client.
* [sic](https://tools.suckless.org/sic/) - sic is an extremely simple IRC client. It consists of less than 250 lines of code.
* [TUIR](https://gitlab.com/ajak/tuir) - Text-based interface (TUI) to view and interact with Reddit from your terminal; TUIR is a fork of rtv, featuring vim keybindings and themes.
* [WeeChat](https://weechat.org/) - WeeChat is a fast, light and extensible chat client, with a text-based user interface, designed to be light and extensible: a lightweight core with optional plugins.

## <a name="networking"></a>Networking

Networks and communication tools: bandwidth monitoring, packet inspection, remote connection, VPNs, terminal sharing, etc..

* [GoTTY](https://github.com/yudai/gotty) ⭐ 19,548 | 🐛 158 | 🌐 Go | 📅 2024-08-01 - Turn CLI tools into web applications; basically, it runs a command and starts a server so that the output can be displayed in a web page.
* [sshuttle](https://github.com/sshuttle/sshuttle) ⭐ 13,526 | 🐛 212 | 🌐 Python | 📅 2026-08-24 - Transparent proxy server that works as a poor man's VPN. Forwards over ssh. Doesn't require admin. Works with Linux and macOS. Supports DNS tunneling.
* [gping](https://github.com/orf/gping) ⭐ 12,641 | 🐛 52 | 🌐 Rust | 📅 2026-08-24 - Ping, but with a graph.
* [ttyd](https://github.com/tsl0922/ttyd) ⭐ 12,255 | 🐛 113 | 🌐 C | 📅 2026-08-12 - Share your terminal over the web.
* [bandwhich](https://github.com/imsnif/bandwhich) ⭐ 11,917 | 🐛 55 | 🌐 Rust | 📅 2026-08-01 - Terminal bandwidth utilization tool.
* [bore](https://github.com/ekzhang/bore) ⭐ 11,424 | 🐛 14 | 🌐 Rust | 📅 2026-02-04 - A simple CLI tool for making tunnels to localhost.
* [wuzz](https://github.com/asciimoo/wuzz) ⭐ 10,721 | 🐛 42 | 🌐 Go | 📅 2026-08-04 - Interactive CLI tool for HTTP inspection.
* [oha](https://github.com/hatoo/oha) ⭐ 10,504 | 🐛 57 | 🌐 Rust | 📅 2026-08-23 - oha is a tiny program that sends some load to a web application and show real-time TUI.
* [serve](https://github.com/vercel/serve) ⭐ 9,895 | 🐛 149 | 🌐 TypeScript | 📅 2026-06-30 - Serves a static site, single page application, or just a static file, and provides a neat interface for listing the directory's contents.
* [websocat](https://github.com/vi/websocat) ⭐ 8,673 | 🐛 158 | 🌐 Rust | 📅 2026-08-13 - Netcat, curl and socat for WebSockets.
* [sshx](https://github.com/ekzhang/sshx) ⭐ 7,652 | 🐛 26 | 🌐 Rust | 📅 2025-06-19 - Fast, collaborative live terminal sharing over the web.
* [trippy](https://github.com/fujiapple852/trippy) ⭐ 7,528 | 🐛 77 | 🌐 Rust | 📅 2026-08-24 - A network diagnostic tool.
* [dog](https://github.com/ogham/dog) ⭐ 6,688 | 🐛 79 | 🌐 Rust | 📅 2024-05-29 - dog is a command-line DNS client. It has colorful output, understands normal command-line argument syntax, supports the DNS-over-TLS and DNS-over-HTTPS protocols, and can emit JSON.
* [AutoRecon](https://github.com/Tib3rius/AutoRecon) ⭐ 6,089 | 🐛 42 | 🌐 Python | 📅 2026-01-28 - AutoRecon is a multi-threaded network reconnaissance tool which performs automated enumeration of services.
* [xxh](https://github.com/xxh/xxh) ⭐ 6,075 | 🐛 30 | 🌐 Python | 📅 2026-06-02 - Bring your favorite shell wherever you go through the ssh.
* [sslh](https://github.com/yrutschle/sslh) ⭐ 5,107 | 🐛 48 | 🌐 C | 📅 2026-08-20 - A ssl/ssh multiplexer (Applicative Protocol Multiplexer) that allows, for example, to share SSH and HTTPS on the same port.
* [Kyanos](https://github.com/hengyoush/kyanos) ⭐ 5,065 | 🐛 32 | 🌐 C | 📅 2026-08-20 - Kyanos is a networking analysis tool using eBPF. It can visualize the time packets spend in the kernel, capture requests/responses, makes troubleshooting more efficient.
* [rustnet](https://github.com/domcyrus/rustnet) ⭐ 4,916 | 🐛 17 | 🌐 Rust | 📅 2026-08-24 - Cross-platform network monitoring tool with a TUI displaying real-time information about network connections.
* [ATAC](https://github.com/Julien-cpsn/ATAC) ⭐ 3,703 | 🐛 19 | 🌐 Rust | 📅 2026-08-23 - Arguably a Terminal API Client. It is based on well-known clients such as Postman, Insomnia, or even Bruno, but inside your terminal without any specific graphical environment needed; free, account-less, and offline for now and forever.
* [tproxy](https://github.com/kevwan/tproxy) ⭐ 3,699 | 🐛 6 | 🌐 Go | 📅 2026-07-09 - A CLI tool to proxy and analyze TCP connections.
* [mtr](https://github.com/traviscross/mtr) ⭐ 3,337 | 🐛 137 | 🌐 C | 📅 2026-06-16 - mtr combines the functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
* [trzsz-ssh](https://github.com/trzsz/trzsz-ssh) ⭐ 2,694 | 🐛 33 | 🌐 Go | 📅 2026-08-15 - An ssh client designed as a drop-in replacement for the openssh client. It aims to provide complete compatibility with openssh, mirroring all its features, while also offering additional useful features. Such as login prompt, batch login, remember password, automated interaction, trzsz, zmodem(rz/sz), udp mode like mosh, etc.
* [oryx](https://github.com/pythops/oryx) ⭐ 2,562 | 🐛 5 | 🌐 Rust | 📅 2026-07-17 - TUI for sniffing network traffic using eBPF on Linux.
* [gg](https://github.com/mzz2017/gg) ⭐ 1,930 | 🐛 48 | 🌐 Go | 📅 2026-07-06 - A command-line tool for one-click proxy in your research and development without installing v2ray or anything else.
* [asn](https://github.com/nitefood/asn) ⭐ 1,926 | 🐛 3 | 🌐 Shell | 📅 2026-06-22 - Server for the following services: ASN, RPKI validity, BGP stats, IPv4v6, Prefix, URL, ASPath, Organization, IP reputation, IP geolocation, IP fingerprinting, Network recon, lookup API server, Web traceroute server.
* [Tunnelmole](https://github.com/robbie-cahill/tunnelmole-client) ⭐ 1,884 | 🐛 17 | 🌐 TypeScript | 📅 2026-04-13 - Connect to local servers from anywhere.
* [netscanner](https://github.com/Chleba/netscanner) ⭐ 1,813 | 🐛 6 | 🌐 Rust | 📅 2026-07-06 - All-in-one network scanning tool.
* [Wishlist](https://github.com/charmbracelet/wishlist) ⭐ 1,651 | 🐛 19 | 🌐 Go | 📅 2026-08-12 - With Wishlist you can have a single entrypoint for multiple SSH endpoints.
* [sshs](https://github.com/quantumsheep/sshs) ⭐ 1,574 | 🐛 25 | 🌐 Rust | 📅 2026-07-09 - Terminal user interface for SSH.
* [kftray](https://github.com/hcavarsan/kftray) ⭐ 1,553 | 🐛 19 | 🌐 Rust | 📅 2026-08-24 - kubectl port-forward on steroids, manage and share multiple k8s port forwards, with support for UDP, proxy through the k8s cluster, and github state sync.
* [bmon](https://github.com/tgraf/bmon) ⭐ 1,383 | 🐛 38 | 🌐 C | 📅 2026-08-24 - A monitoring and debugging tool to capture networking related statistics and prepare them visually in a human friendly way.
* [wavemon](https://github.com/uoaerg/wavemon) ⭐ 1,228 | 🐛 6 | 🌐 C | 📅 2026-06-29 - wavemon is an ncurses-based monitoring application for wireless network devices on Linux.
* [sngrep](https://github.com/irontec/sngrep) ⭐ 1,203 | 🐛 74 | 🌐 C | 📅 2026-08-17 - Ncurses SIP Messages flow viewer.
* [xiringuito](https://github.com/ivanilves/xiringuito) ⭐ 1,160 | 🐛 8 | 🌐 Shell | 📅 2021-12-29 - VPN made easy! No configuration. No VPN servers. No hassle. Using SSH capabilities.
* [ggh](https://github.com/byawitz/ggh) ⭐ 950 | 🐛 26 | 🌐 Go | 📅 2026-02-10 - Recall your SSH sessions, also searching your SSH config file.
* [Rustcat](https://github.com/robiot/rustcat) ⭐ 810 | 🐛 4 | 🌐 Rust | 📅 2024-07-20 - Netcat Alternative in Rust.
* [MQTT TUI](https://github.com/EdJoPaTo/mqttui) ⭐ 719 | 🐛 10 | 🌐 Rust | 📅 2026-08-09 - MQTT Client written in rust (Subscribe to a MQTT topic or publish something quickly).
* [speedtest-net](https://github.com/ddsol/speedtest.net) ⭐ 624 | 🐛 18 | 🌐 JavaScript | 📅 2022-02-11 - Test internet connection speed and ping using speedtest.net.
* [Kapow!](https://github.com/BBVA/kapow) ⭐ 623 | 🐛 32 | 🌐 Go | 📅 2024-10-23 - Say we have a nice cozy shell command that solves our problem. Kapow! lets us easily turn that into an HTTP API.
* [tsshd](https://github.com/trzsz/tsshd) ⭐ 532 | 🐛 0 | 🌐 Go | 📅 2026-07-25 - The tsshd works like mosh-server, while the "tssh --udp" works like mosh. Supports ssh port forwarding, ssh agent forwarding and X11 forwarding.
* [dug](https://github.com/unfrl/dug) ⭐ 371 | 🐛 13 | 🌐 C# | 📅 2026-01-11 - A global DNS propagation checker that gives pretty output.
* [chiko](https://github.com/felangga/chiko) ⭐ 353 | 🐛 0 | 🌐 Go | 📅 2026-04-15 - The ultimate beauty gRPC Client on your Terminal: a simple tool to interact with gRPC services using a beautiful terminal interface.
* [havn](https://github.com/mrjackwills/havn) ⭐ 318 | 🐛 2 | 🌐 Rust | 📅 2026-08-23 - A fast configurable port scanner with reasonable defaults.
* [packemon](https://github.com/ddddddO/packemon) ⭐ 305 | 🐛 36 | 🌐 Go | 📅 2026-08-21 - TUI tool and Go library for sending packets of arbitrary input and monitoring packets on any network interfaces (default: eth0).
* [dish](https://github.com/thevxn/dish) ⭐ 280 | 🐛 1 | 🌐 Go | 📅 2026-06-04 - A lightweight, remotely configurable monitoring service.
* [TStream](https://github.com/qnkhuat/tstream) ⭐ 269 | 🐛 1 | 🌐 Go | 📅 2022-07-01 - Live streaming from the terminal. Requires the connection to a central server, from which the streaming is dispatched.
* [neoss](https://github.com/PabloLec/neoss) ⭐ 229 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-17 - User-friendly and detailed socket statistics with a Terminal UI.
* [CuTE](https://github.com/PThorpe92/CuTE) ⚠️ Archived - TUI to help build, execute and save curl commands, recursively download from remote sources, test your API endpoints, and mange your keys.
* [liboping](https://github.com/octo/liboping) ⭐ 216 | 🐛 51 | 🌐 C | 📅 2023-01-24 - Protocol independent ANSI-C ping library and command line utility.
* [sshsync](https://github.com/Blackmamoth/sshsync) ⭐ 159 | 🐛 3 | 🌐 Python | 📅 2025-06-18 - Fast and minimal CLI tool to run shell commands across multiple remote servers via SSH.
* [humble-explorer](https://github.com/koenvervloesem/humble-explorer) ⭐ 84 | 🐛 0 | 🌐 Python | 📅 2023-11-25 - Cross-platform, command-line and human-friendly Bluetooth Low Energy scanner.
* [hflow](https://github.com/comradequinn/hflow) ⭐ 80 | 🐛 0 | 🌐 Go | 📅 2023-06-02 - A command-line, debugging http/s proxy server.
* [TReq](https://github.com/talis-fb/TReq) ⭐ 66 | 🐛 17 | 🌐 Rust | 📅 2024-10-28 - A CLI tool for effortless HTTP requests.
* [fwtui](https://github.com/Beny406/fwtui) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2025-06-09 - TUI built in Go to help you manage UFW rules with ease.
* [SMBScan](https://github.com/jeffhacks/smbscan) ⭐ 50 | 🐛 19 | 🌐 Python | 📅 2026-08-18 - SMBScan is a tool to enumerate file shares on an internal network.
* [ttfb](https://github.com/phip1611/ttfb) ⭐ 49 | 🐛 4 | 🌐 Rust | 📅 2026-07-01 - ttfb is a CLI-Tool to measure the TTFB (time to first byte) of HTTP requests.
* [redive](https://github.com/neelkarma/redive) ⭐ 47 | 🐛 0 | 🌐 Rust | 📅 2024-12-29 - Trace URL redirections in the terminal.
* [termishare](https://github.com/qnkhuat/termishare) ⭐ 38 | 🐛 1 | 🌐 Go | 📅 2022-03-13 - Peer to peer terminal sharing.
* [tunblkctl](https://github.com/azhuchkov/tunblkctl) ⭐ 38 | 🐛 8 | 🌐 Shell | 📅 2025-09-11 - Command-line frontend for Tunnelblick.
* [portfinder](https://github.com/doganarif/portfinder) ⭐ 37 | 🐛 2 | 🌐 Go | 📅 2026-06-23 - Modern CLI tool to identify and manage processes using network ports; Built with GO, featuring project awareness, Docker support and an interactive terminal UI.
* [netdump](https://github.com/giorgiopapini/netdump) ⭐ 36 | 🐛 1 | 🌐 C | 📅 2025-09-01 - A simple network packet analyzer using libpcap, supporting both real-time and offline analysis with ASCII visualization.
* [adless](https://github.com/WIttyJudge/adless) ⭐ 32 | 🐛 3 | 🌐 Go | 📅 2024-12-16 - Local domains blocker written in Go.
* [Thymus](https://github.com/blademd/thymus) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2024-06-04 - An interactive browser & editor for network configuration files.
* [recon](https://github.com/jreisinger/recon) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2024-07-25 - Gather public info about network hosts.
* [ssh-menu](https://github.com/antonjah/ssh-menu) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2019-12-02 - A very simple terminal tool that renders an interactive menu with your ssh profiles listed.
* [quickserve](https://github.com/haileys/quickserve) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2012-11-02 - Very simple HTTP server written in Python for quickly sharing files on an ad-hoc basis. Aside from opening a port in your firewall if you have one, it requires no setup and should work with no hassle.
* [turl](https://github.com/yilmaz08/turl) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2024-07-27 - tURL is a command-line tool to make plain TCP-based requests.
* [nics](https://github.com/jftuga/nics) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2026-07-06 - Display information about Network Interface Cards (NICs); the same output is presented across platforms.
* [TGORQ](https://github.com/vitor-augusto1/tgorq) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2024-06-04 - Terminal GO ReQuest (TGORQ) is a Vim-like lightweight CLI tool for performing HTTP requests.
* [echo](https://github.com/devem-tech/echo) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2024-10-09 - Speedy API emulation facilitated by a reverse proxy and mock JSON server.
* [darkhttpd](https://unix4lyfe.org/darkhttpd/) - Darkhttpd is a simple, fast HTTP 1.1 web server for static content. It does not support PHP or CGI etc but is designed to serve static content, which it does very well.
* [doggo](https://doggo.mrkaran.dev/) - DNS client for humans. Features include: colors, tabular and JSON formats, and reverse DNS lookup.
* [ejabberd](https://www.ejabberd.im/) - ejabberd is an XMPP application server and an MQTT broker, written mainly in the Erlang programming language.
* [generate-ip](https://generate-ip.org) - Randomly generate, format, and validate IPv4 + IPv6 + MAC addresses.
* [geolocate](https://github.com/adamlui/js-utils/tree/main/geolocate/#readme) - Fetch IP geolocation data.
* [ipcalc](http://jodies.de/ipcalc) - Takes an IP address and netmask and calculates the resulting broadcast, network, Cisco wildcard mask, and host range.
* [mitmproxy](https://mitmproxy.org/) - An interactive HTTPS proxy.
* [mosh](https://mosh.org/) - Remote SSH client that achieve good responsiveness in presence of intermittent connectivity and roaming.
* [Optic](https://www.useoptic.com/) - Optic's Open Source tools make OpenAPI and API-first practices easy for any team to adopt.
* [Prosody](https://prosody.im/) - Prosody is a modern XMPP communication server. It aims to be easy to set up and configure, and efficient with system resources.
* [Proxymock](https://proxymock.io) - A network recorder that shows API payloads in a TUI and automatically generates tests and mocks from what it observes.
* [PSSH](https://code.google.com/archive/p/parallel-ssh/) - Parallelized versions of OpenSSH and related tools, such as pssh, pscp, prsync, pnuke, and pslurp. The project includes psshlib which can be used within custom applications.
* [quark](https://tools.suckless.org/quark/) - quark is an extremely small and simple HTTP GET/HEAD-only web server for static content.
* [rtop](http://www.rtop-monitor.org/) - Simple, agent-less, remote server monitoring tool that works over plain SSH. Written in Go, it does not need any software to be installed on the server that you want to monitor. It works by establishing an SSH session, and running commands on the remote server to collect system metrics.
* [Seashells](https://seashells.io/) - Pipe output to the web.
* [Termshark](https://termshark.io/) - A terminal UI for tshark, inspired by Wireshark.
* [zxc](https://hail-hydrant.github.io/zxc/) - Terminal based intercepting proxy written in rust with tmux and vim as user interface.

## <a name="connection-manager"></a>Connection managers

Manage Bluetooth and Wifi networks, and SSH connections.

* [bluetui](https://github.com/pythops/bluetui) ⭐ 2,971 | 🐛 21 | 🌐 Rust | 📅 2026-07-17 - A TUI for managing bluetooth devices on Linux.
* [impala](https://github.com/pythops/impala) ⭐ 2,795 | 🐛 5 | 🌐 Rust | 📅 2026-08-24 - TUI for managing wifi networks and connections on Linux.
* [bluetuith](https://github.com/darkhz/bluetuith) ⭐ 1,390 | 🐛 11 | 🌐 Go | 📅 2026-07-01 - A TUI-based Bluetooth connection manager, which can interact with Bluetooth adapters and devices. It aims to be a replacement to most Bluetooth managers, like blueman.
* [sshto](https://github.com/vaniacer/sshto) ⭐ 651 | 🐛 6 | 🌐 Shell | 📅 2026-06-19 - Small bash script to manage your ssh connections. It builds menu (via dialog) from your \~/.ssh/config. It can not only connect but also to run commands, copy files, tunnel ports.
* [goto](https://github.com/grafviktor/goto) ⭐ 533 | 🐛 11 | 🌐 Go | 📅 2026-07-09 - A simple terminal SSH manager that provides you with an easy access to the list of your favorite SSH servers, binaries included.
* [sshed](https://github.com/trntv/sshed) ⭐ 159 | 🐛 5 | 🌐 Go | 📅 2024-05-23 - sshed is a ssh config editor and bookmarks manager.
* [ssm](https://github.com/lfaoro/ssm) ⭐ 112 | 🐛 15 | 🌐 Go | 📅 2026-08-24 - SSH connection manager designed to connect, filter, tag, and much more from a simple terminal interface.
* [blueutil-tui](https://github.com/Zaloog/blueutil-tui) ⭐ 53 | 🐛 0 | 🌐 Python | 📅 2025-08-17 - TUI for Mac to interact with bluetooth devices via blueutil.
* [SSM](https://github.com/elliot40404/ssm) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2023-09-17 - A simple SSH manager.
* [SSHop](https://github.com/Skullsneeze/sshop) ⭐ 14 | 🐛 1 | 🌐 Shell | 📅 2025-06-11 - An SSH connection helper that let's you hop to a server with ease.
* [sshbook](https://github.com/edavlis/sshbook) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-07-04 - Minimal terminal-based SSH launcher for saving ssh entries.
* [NetworkManager](https://developer.gnome.org/NetworkManager/stable/nmtui.html) - Will connect any network device when a connection for that device becomes available, unless it is disabled, by managing the primary network connection and other network interfaces (Ethernet, Wi-Fi and Mobile Broadband devices).

## <a name="transfer"></a>Data transfer

Programs for transferring files and data between different machines.

* [yt-dlp](https://github.com/yt-dlp/yt-dlp) ⭐ 186,727 | 🐛 2,606 | 🌐 Python | 📅 2026-08-25 - A youtube-dl fork with additional features and fixes.
* [youtube-dl](https://github.com/ytdl-org/youtube-dl) ⭐ 141,017 | 🐛 4,128 | 🌐 Python | 📅 2026-02-19 - Downloads videos from [YouTube](https://www.youtube.com/) and some other sites useful for automated bulk downloads.
* [aria2](https://github.com/aria2/aria2) ⭐ 41,812 | 🐛 1,175 | 🌐 C++ | 📅 2026-06-25 - Lightweight and easy-to-use download utility; it supports HTTP/HTTPS, FTP, SFTP, BitTorrent, Metalink and multiple sources; cross-platform.
* [croc](https://github.com/schollz/croc) ⭐ 40,082 | 🐛 2 | 🌐 Go | 📅 2026-08-24 - Easily and securely send things from one computer to another.
* [lux](https://github.com/iawia002/lux) ⭐ 31,655 | 🐛 546 | 🌐 Go | 📅 2026-03-29 - Lux is a fast and simple video downloader built with Go.
* [Magic Wormhole](https://github.com/magic-wormhole/magic-wormhole) ⭐ 22,868 | 🐛 181 | 🌐 Python | 📅 2026-08-25 - The program allows transfer arbitrary-sized files and directories (or short pieces of text) from one computer to another The two endpoints are identified by using identical human-readable codes.
* [gallery-dl](https://github.com/mikf/gallery-dl) ⭐ 19,312 | 🐛 1,151 | 🌐 Python | 📅 2026-08-01 - Gallery-dl is a command-line program to download image galleries and collections from several image hosting sites.
* [xh](https://github.com/ducaale/xh) ⭐ 8,039 | 🐛 38 | 🌐 Rust | 📅 2026-08-23 - xh is a friendly and fast tool for sending HTTP requests. It reimplements as much as possible of HTTPie's excellent design.
* [tdl](https://github.com/iyear/tdl) ⭐ 7,969 | 🐛 182 | 🌐 Go | 📅 2026-08-24 - Beautiful and feature-rich Telegram downloader, written in Go.
* [ffsend](https://github.com/timvisee/ffsend) ⭐ 7,375 | 🐛 33 | 🌐 Rust | 📅 2025-11-20 - Easily and securely share files from the command line. A fully featured Firefox Send client.
* [zrok](https://github.com/openziti/zrok) ⭐ 4,641 | 🐛 123 | 🌐 Go | 📅 2026-06-22 - Geo-scale, next-generation peer-to-peer sharing platform built on top of OpenZiti.
* [ytfzf](https://github.com/pystardust/ytfzf) ⭐ 4,147 | 🐛 66 | 🌐 Shell | 📅 2024-09-27 - A POSIX script that helps you find YouTube videos (without API) and opens/downloads them using mpv/youtube-dl.
* [curlie](https://github.com/rs/curlie) ⭐ 3,712 | 🐛 25 | 🌐 Go | 📅 2025-12-07 - The power of curl, the ease of use of httpie.
* [ytmdl](https://github.com/deepjyoti30/ytmdl) ⭐ 3,530 | 🐛 17 | 🌐 Python | 📅 2024-08-15 - Get songs from YouTube in mp3 format.
* [termscp](https://github.com/veeso/termscp) ⭐ 3,057 | 🐛 7 | 🌐 Rust | 📅 2026-07-29 - A TUI file transfer and explorer, with support for SCP/SFTP/FTP/S3.
* [Yark](https://github.com/Owez/yark) ⭐ 2,183 | 🐛 21 | 🌐 Python | 📅 2026-07-30 - YouTube archiving made simple.
* [sharing](https://github.com/parvardegr/sharing) ⭐ 1,838 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-17 - Sharing is a command-line tool to share directories and files from the CLI to iOS and Android devices without the need of an extra client app.
* [portal](https://github.com/SpatiumPortae/portal) ⭐ 1,766 | 🐛 29 | 🌐 Go | 📅 2024-08-20 - A quick and easy command-line file transfer utility from any computer to another.
* [qr-filetransfer](https://github.com/sdushantha/qr-filetransfer) ⭐ 1,029 | 🐛 5 | 🌐 Python | 📅 2024-04-10 - Transfer files over Wi-Fi between your computer and your smartphone from the terminal.
* [pbgopy](https://github.com/nakabonne/pbgopy) ⭐ 815 | 🐛 6 | 🌐 Go | 📅 2026-04-29 - Copy and paste between devices.
* [downloader-cli](https://github.com/deepjyoti30/downloader-cli) ⭐ 467 | 🐛 3 | 🌐 Python | 📅 2023-11-23 - A simple downloader written in Python with an awesome customizable progress bar.
* [tran](https://github.com/abdfnx/tran) ⭐ 447 | 🐛 10 | 🌐 Go | 📅 2026-02-16 - Securely transfer and send anything between computers with TUI.
* [Better Curl Saul](https://github.com/DeprecatedLuar/better-curl-saul) ⭐ 319 | 🐛 3 | 🌐 Go | 📅 2026-04-23 - HTTP client with persistent workspace configs and dynamic variables to eliminate API setup repetition.
* [tshare](https://github.com/trikko/tshare) ⭐ 142 | 🐛 0 | 🌐 D | 📅 2023-12-13 - The fastest way to share your files on the web, for free.
* [Jitter](https://github.com/kevspau/jitter) ⚠️ Archived - A repository-oriented binary manager for Linux, Jitter searches through online repository (currently only on GitHub) for releases with .tar.gz, .tgz, .zip or .AppImage assets.
* [rclone-tui](https://github.com/darkhz/rclone-tui) ⭐ 87 | 🐛 0 | 🌐 Go | 📅 2022-12-23 - Cross-platform manager for rclone, which aims to be on-par with the web GUI.
* [shbin](https://github.com/Shiphero/shbin) ⭐ 69 | 🐛 17 | 🌐 Python | 📅 2025-04-22 - Upload code snippets, notebooks, images or any other content to a GitHub repository that acts as your internal pastebin, and returns the URL to share it with your team.
* [github-dlr](https://github.com/rocktimsaikia/github-dlr) ⭐ 59 | 🐛 1 | 🌐 Python | 📅 2026-05-06 - Download individual files and folders from Github recursively.
* [ytdl-tui](https://github.com/darky/ytdl-tui) ⭐ 39 | 🐛 0 | 🌐 TypeScript | 📅 2024-12-21 - TUI for downloading Youtube videos.
* [Nextcloud share URL downloader](https://github.com/aertslab/nextcloud_share_url_downloader) ⭐ 28 | 🐛 3 | 🌐 Shell | 📅 2024-06-18 - Download files from and list content of NextCloud (password protected) share directly from the command line without needing a web browser.
* [newsboat\_video\_downloader](https://github.com/Jocomol/newsboat_video_downloader) ⭐ 27 | 🐛 0 | 🌐 Shell | 📅 2023-09-22 - Downloads content from YouTube and have them sorted into different folders depending on the channel.
* [smartscp](https://github.com/lengyijun/smartscp) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2026-03-07 - A replacement of scp, but auto skip git-ignored files; it's just a wrapper of sshfs and xcp.
* [Froop](https://github.com/happer64bit/froop) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2025-08-07 - Share file across network seamlessly and securely.
* [goop-cli](https://github.com/yojoecapital/goop-cli) ⭐ 2 | 🐛 1 | 🌐 C# | 📅 2025-08-06 - The Google Drive Push CLI is a simple tool for syncing files between a local directory and Google Drive.
* [Filebin cli](https://github.com/mshirazkamran/filebin-api) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-09-18 - CLI tool to share files temporarily from the terminal (share short code to download on the other machine).
* [curl](https://curl.haxx.se/) - A tool and library for transferring data with URL syntax, supports a lot of protocols.
* [dlvr.sh](https://dlvr.sh/) - CLI for temporary file delivery: upload local files, create controlled share links, download shares, and manage deliveries from scripts and automation.
* [lftp](https://lftp.yar.ru/) - "Sophisticated FTP/HTTP client, and a file transfer program supporting a number of network protocols"; support for bookmarks and mirroring features.
* [OnionShare](https://onionshare.org/) - "An open source tool that lets you securely and anonymously share a file of any size."
* [osync](http://www.netpower.fr/osync) - A robust two-way (bidirectional) file sync script based on rsync with fault tolerance, POSIX ACL support, time control and near real-time sync.
* [qrcp](https://www.linuxuprising.com/2020/07/qrcp-transfer-files-between-desktop-and.html) - Transfer Files Between Desktop And Mobile Devices Over Wi-Fi By Scanning A QR Code.
* [rclone](https://rclone.org/) - Manage file synchronization on cloud storage.
* [rsync](https://download.samba.org/pub/rsync/rsync.html) - A tool that mirrors directories across networked machines, handling changes to files, working across SSH, with plenty of parameters for configuration.
* [sitecopy](http://www.manyfish.co.uk/sitecopy/) - Synchronizes a local copy of a website with a remote copy on a server, does not use SSH/`scp` but FTP for file copy, useful when the remote server does not support secure copy.
* [stftp](http://stftp.sourceforge.net/) - (simple terminal FTP) aims to be an "easy-to-use and unbloated client for the UNIX (and UNIX-like) console".
* [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - File synchronizer. It allows two replicas of a collection of files and directories to be stored on different hosts (or different disks on the same host), modified separately, and then brought up to date by propagating the changes in each replica to the other.
* [Woof](http://www.home.unix-ag.org/simon/woof.html) - (Web Offer One File) sets up an HTTP webserver to serve files from a given local directory all the users connected to the network can see and download the files.

## <a name="torrent"></a>Torrent

Clients and download managers using the BitTorrent protocol.

* [rtorrent](https://github.com/rakshasa/rtorrent) ⭐ 4,847 | 🐛 397 | 🌐 C++ | 📅 2026-08-24 - BitTorrent client uses ncurses and is ideal for use with tmux, screen or dtach.
* [Torrra](https://github.com/stabldev/torrra) ⭐ 1,222 | 🐛 2 | 🌐 Python | 📅 2026-08-25 - A Python tool that lets you find and download torrents without leaving your CLI.
* [nyaa](https://github.com/Beastwick18/nyaa) ⭐ 693 | 🐛 16 | 🌐 Rust | 📅 2026-02-28 - A nyaa TUI for browsing and downloading torrents.
* [Stig](https://github.com/rndusr/stig) ⭐ 628 | 🐛 53 | 🌐 Python | 📅 2026-01-24 - Stig is a client application to connect and control the BitTorrent Transmission client app.
* [Mabel](https://github.com/smmr-software/mabel) ⭐ 437 | 🐛 5 | 🌐 Go | 📅 2023-08-22 - A fancy BitTorrent client for the terminal built with Go and the Bubbletea library.
* [toru](https://github.com/sweetbbak/toru) ⭐ 388 | 🐛 1 | 🌐 Go | 📅 2024-10-24 - BitTorrent streaming CLI tool to stream anime torrents in real-time with no waiting for downloads.
* [Transgression TUI](https://github.com/PanAeon/transg-tui) ⭐ 109 | 🐛 6 | 🌐 Rust | 📅 2026-03-02 - A remote TUI client for the Transmission BitTorrent program.
* [torrentCLI](https://github.com/amogusussy/torrentCLI) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2023-04-09 - Get torrents from the Terminal.
* [Deluge](http://deluge-torrent.org/) - A lightweight, Free Software, cross-platform BitTorrent client; a terminal curses interface, web interface and command line client can connect to a running daemon to manage torrent downloads.
* [Transmission](https://transmissionbt.com/) - Fast, easy and free BitTorrent client.

## <a name="rss"></a>RSS

RSS feed visualizers, converters, and managers.

* [nom](https://github.com/guyfedwards/nom) ⭐ 740 | 🐛 33 | 🌐 Go | 📅 2026-07-08 - RSS reader for the terminal.
* [TermFeed](https://github.com/iamaziz/TermFeed) ⭐ 261 | 🐛 11 | 🌐 Python | 📅 2023-06-12 - A simple terminal feed reader.
* [Canard](https://github.com/mrusme/canard) ⚠️ Archived - A command line TUI client for the Journalist RSS aggregator.
* [Canto Curses](https://github.com/themoken/canto-curses) ⭐ 95 | 🐛 3 | 🌐 Python | 📅 2025-01-08 - Curses frontend for [Canto daemon](https://github.com/themoken/canto-next) ⭐ 160 | 🐛 5 | 🌐 Python | 📅 2020-12-08 for RSS feeds.
* [Terminal-yt](https://github.com/jooooscha/terminal-yt) ⭐ 44 | 🐛 3 | 🌐 Rust | 📅 2026-01-06 - A small newsboat-inspired terminal youtube manager written in Rust; (fetches video from atom and RSS feeds, opens them in a video player)
* [rss-cli](https://github.com/Clortox/rss-cli) ⭐ 25 | 🐛 1 | 🌐 C++ | 📅 2024-01-29 - A UNIX-inspired CLI application for interacting with RSS feeds.
* [rReader](https://github.com/rainygirl/rreader) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-06-06 - RSS reader client with TUI interface.
* [feedln](https://github.com/xqtr/feedln) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-07-28 - A simple terminal RSS reader.
* [Newsboat](https://newsboat.org/) - An RSS/Atom feed reader for the text console. It's an actively maintained fork of Newsbeuter.
* [Newsraft](https://codeberg.org/newsraft/newsraft) - Newsraft is a feed reader with ncurses user interface. It is greatly inspired by Newsboat and tries to be its lightweight counterpart.
* [openring](https://git.sr.ht/~sircmpwn/openring) - A tool for generating a webring from RSS feeds, so you can link to other blogs you like on your own blog.
* [Sfeed](https://codemadness.org/sfeed.html) - Sfeed is a RSS and Atom parser (and some format programs). It converts RSS or Atom feeds from XML to a TAB-separated file.

## <a name="browser"></a>Web browser

Web browsers with textual interface.

* [carbonyl](https://github.com/fathyb/carbonyl) ⭐ 19,467 | 🐛 90 | 🌐 Rust | 📅 2024-07-01 - Chromium running inside your terminal.
* [s](https://github.com/zquestz/s) ⭐ 2,597 | 🐛 0 | 🌐 Go | 📅 2026-07-27 - Web search from the terminal. Just opens in your browser.
* [Amfora](https://github.com/makew0rld/amfora) ⭐ 1,353 | 🐛 10 | 🌐 Go | 📅 2026-07-03 - Amfora aims to be the best looking Gemini client with the most features. It does not support Gopher or other non-Web protocols.
* [Graphene](https://github.com/atsepkov/Graphene) ⭐ 74 | 🐛 1 | 🌐 JavaScript | 📅 2019-08-30 - A text-based web browser that's a joy to use.
* [gplaces](https://github.com/dimkr/gplaces) ⭐ 49 | 🐛 1 | 🌐 C | 📅 2026-06-18 - Simple but powerful terminal Gemini client.
* [min](https://github.com/a-h/min) ⭐ 44 | 🐛 0 | 🌐 Go | 📅 2021-07-21 - A Gemini browser with Vim style keyboard navigation, client certificate support and history and bookmarks saved in TSV files.
* [cli-arxiv](https://github.com/knguyenanhoa/cli-arxiv) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2025-05-08 - CLI tool for exploring arXiv.
* [Litter](https://github.com/tuxcanfly/litter) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2025-06-27 - Litter is a minimalistic, terminal-based read-only browser that allows users to browse the web without the bloat and distractions of modern web browsers.
* [Gremlin](https://github.com/actuday6418/gremlin) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2021-12-03 - Gemini browser for the terminal.
* [Romulus](https://github.com/LukeEmmet/Romulus) ⭐ 13 | 🐛 3 | 🌐 C# | 📅 2022-07-21 - A cross-platform Gemini console client in C# with a simple user interface, interactive menus and mouse support.
* [asuka](https://git.sr.ht/~julienxx/asuka) - A Gemini Project client written in Rust with ncurses.
* [Bombadillo](https://bombadillo.colorfield.space/) - A non-web browser, designed for a growing list of protocols operating outside of the web. Currently supports Gemini, Finger and Gopher.
* [browsh](https://www.brow.sh/) - It renders anything that a modern browser can; HTML5, CSS3, JS, video and even WebGL. Its main purpose is to be run on a remote server and accessed via SSH/Mosh or the in-browser HTML service in order to significantly reduce bandwidth and thus both increase browsing speeds and decrease bandwidth costs.
* [Chawan](https://sr.ht/~bptato/chawan/) - A text-mode web browser. It displays websites in your terminal and allows you to navigate on them. It can also be used as a terminal pager.
* [ELinks](http://elinks.cz/) - Fork of ELinks, feature-rich text mode web browser(http, ftp); Can render both frames and tables, it's customizable and can be extended via scripts.
* [Links](http://www.jikos.cz/~mikulas/links//) - A textual Web browser with tables and frames.
* [Lynx](http://lynx.invisible-island.net/) - A highly configurable text-based web browser, one of the oldest CLI browser I'm aware of.
* [Telescope](https://telescope.omarpolo.com/) - Gemini client with UI that is strongly inspired from Emacs and W3M.
* [w3m](http://w3m.sourceforge.net/) - A text-based web browser as well as a pager like `less`, it can be used as a text formatting tool which typesets HTML into plain text.

## <a name="online"></a>Online search and resources

Tools that interact with online resources to provide their services, e.g., searches, wiki, etc..

* [jira-cli](https://github.com/ankitpokhrel/jira-cli) ⭐ 5,912 | 🐛 162 | 🌐 Go | 📅 2026-08-19 - Feature-rich interactive Jira command line.
* [ddgr](https://github.com/jarun/ddgr) ⭐ 3,534 | 🐛 1 | 🌐 Python | 📅 2026-08-16 - A command line utility to search DuckDuckGo (HTML version) from the terminal.
* [socialscan](https://github.com/iojw/socialscan) ⭐ 1,825 | 🐛 14 | 🌐 Python | 📅 2026-08-03 - Python library and CLI for accurately querying username and email usage on online platforms.
* [so](https://github.com/samtay/so) ⭐ 1,423 | 🐛 19 | 🌐 Rust | 📅 2025-06-30 - Terminal interface for Stack Overflow.
* [socli](https://github.com/gautamkrishnar/socli) ⭐ 1,111 | 🐛 11 | 🌐 Python | 📅 2026-03-30 - Stack overflow command line client written in Python. Search and browse stack overflow without leaving the terminal
* [STU](https://github.com/lusingander/stu) ⭐ 907 | 🐛 15 | 🌐 Rust | 📅 2026-04-30 - S3 Terminal UI, is a interactive terminal-based explorer for Amazon S3 (AWS S3).
* [Awesome CLI](https://github.com/umutphp/awesome-cli) ⭐ 806 | 🐛 2 | 🌐 Go | 📅 2025-10-08 - Awesome CLI is a simple command line tool to give you a fancy command line interface to dive into Awesome lists.
* [wiki-tui](https://github.com/Builditluc/wiki-tui) ⚠️ Archived - A simple and easy to use Wikipedia Text User Interface.
* [Neon Modem Overdrive](https://github.com/mrusme/neonmodem) ⭐ 701 | 🐛 21 | 🌐 Go | 📅 2026-07-21 - The program allows you to manage and read content from various popular platforms without having to use a browser or separate apps.
* [av](https://github.com/aviator-co/av) ⭐ 509 | 🐛 73 | 🌐 Go | 📅 2026-08-24 - A command line tool to manage stacked PRs with Aviator.
* [pockyt](https://github.com/achembarpu/pockyt) ⭐ 498 | 🐛 5 | 🌐 Python | 📅 2024-04-25 - Read, manage, and automate the collection of articles in [Pocket](https://getpocket.com), an application for managing a reading list of articles from the Internet.
* [wikit](https://github.com/KorySchneider/wikit) ⭐ 291 | 🐛 5 | 🌐 JavaScript | 📅 2026-04-02 - A command line program for getting Wikipedia summaries easily.
* [Awesome Finder](https://github.com/mingrammer/awesome-finder) ⭐ 284 | 🐛 10 | 🌐 Python | 📅 2022-12-08 - Search the awesome lists from the command line.
* [Fjira](https://github.com/mk-5/fjira) ⭐ 273 | 🐛 22 | 🌐 Go | 📅 2026-07-07 - The fuzziest Jira command line tool in the world.
* [Reddittui](https://github.com/tonymajestro/reddit-tui) ⭐ 231 | 🐛 14 | 🌐 Go | 📅 2025-05-28 - Terminal UI for reddit.
* [moviemon](https://github.com/iCHAIT/moviemon) ⭐ 229 | 🐛 6 | 🌐 Python | 📅 2016-11-19 - A Python program that displays all the information about all your movies in the command line.
* [par\_scrape](https://github.com/paulrobello/par_scrape) ⭐ 218 | 🐛 10 | 🌐 Python | 📅 2026-07-12 - PAR Scrape is a versatile web scraping tool with options for Selenium or Playwright, featuring AI-powered data extraction and formatting.
* [is-fast](https://github.com/Magic-JD/is-fast) ⭐ 169 | 🐛 3 | 🌐 Rust | 📅 2025-11-03 - A TUI tool designed for quick and efficient internet searches directly from the terminal, ideal for environments where you don't have easy access to a browser.
* [MAL-Cli](https://github.com/L4z3x/mal-cli) ⭐ 159 | 🐛 0 | 🌐 Rust | 📅 2025-07-17 - A terminal interface for the official myanimelist api written in Rust and Ratatui.
* [pure-recipe](https://github.com/atiumcache/pure-recipe) ⭐ 92 | 🐛 3 | 🌐 Python | 📅 2024-07-13 - Input a recipe URL and receive well-formatted, ad-free recipes to your terminal, or save the output to a Markdown file.
* [IMDb Terminal Browser](https://github.com/isene/IMDB) ⭐ 75 | 🐛 0 | 🌐 Ruby | 📅 2026-04-11 - Ruby-based terminal application for discovering and managing movies and TV series from IMDb's Top lists.
* [ghfetch](https://github.com/orangekame3/ghfetch) ⭐ 67 | 🐛 3 | 🌐 Go | 📅 2026-08-25 - ghfetch is a CLI tool to fetch GitHub user information and show like Neofetch.
* [tblogs](https://github.com/ezeoleaf/tblogs) ⭐ 65 | 🐛 5 | 🌐 Go | 📅 2026-07-03 - Read and browse development blogs with this TUI from your terminal.
* [arch-wiki](https://github.com/deadhead420/arch-wiki) ⭐ 29 | 🐛 1 | 🌐 Shell | 📅 2019-05-31 - Search the Arch Wiki anywhere from the command line.
* [flashback](https://github.com/cachebag/flashback) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2025-09-14 - Find old YouTube content that the algorithm hides by searching videos from specific years.
* [RIFT](https://github.com/matthieugusmini/rift) ⭐ 26 | 🐛 13 | 🌐 Go | 📅 2026-07-20 - League of Legends Esports in the terminal.
* [dawson](https://github.com/will-moss/dawson) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2024-09-16 - Track your project's statistics on Hacker News and Github, and get notified on every new interaction.
* [PagerDuty TUI](https://github.com/Mk555/pagerduty-tui) ⭐ 9 | 🐛 2 | 🌐 Rust | 📅 2024-12-11 - Minimalistic terminal UI to manage triggered incidents.
* [Ozeki](https://github.com/fuzzy/ozeki) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-01-17 - Ozeki is a TUI for browsing data from sumo-api and for basho data going back to 1960.
* [subs](https://github.com/0x4f53/subs) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2025-04-30 - Grab valid subdomains, resolve them, split them and more.
* [leetfetch](https://github.com/Rage997/leetfetch) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-06-23 - A commandline python tool to fetch and organize all leetcode submissions and problem description locally.
* [sftui](https://github.com/AdamWHY2K/steam_friends_list_tui) ⭐ 5 | 🐛 12 | 🌐 C# | 📅 2026-01-19 - Real-time command-line interface for viewing your Steam friends list (monitor online status, current games and last seen).
* [Wikipedia-Command-Line-Interface](https://github.com/DaDevMikey/Wikipedia-Command-Line-Interface) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2025-06-13 - Use wikipedia in your command prompt.
* [brave-bookmarks](https://github.com/talwrii/brave-bookmarks) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-04-12 - Command-line script to query Brave's bookmark.
* [gh-star-timeline](https://github.com/talwrii/gh-star-timeline) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-05-01 - Command-line tool to keep track of historic stars on github. Machine-useable output.
* [magic-tape](https://gitlab.com/christosangel/magic-tape) - Magic-tape is an image supporting fuzzy finder command line interface YouTube client.
* [pola](https://github.com/Sethispr/pola) - A TUI for efficiently searching skins, checking values and finding owners in Silent Assassin.
* [Shreddit](https://github.com/x89/Shreddit) - Remove your comment history on Reddit as deleting an account does not do so.
* [tuir](https://gitlab.com/Chocimier/tuir) - Browse Reddit from your terminal.

# <a name="Personal-Information-Management"></a>Personal Information Management

## <a name="todo-manager"></a>Todo managers

Todo list and task managers.

* [taskbook](https://github.com/klaudiosinani/taskbook) ⭐ 9,338 | 🐛 101 | 🌐 JavaScript | 📅 2025-11-03 - Tasks, boards & notes for the command-line habitat.
* [Dooit](https://github.com/kraanzu/dooit) ⭐ 2,938 | 🐛 26 | 🌐 Python | 📅 2026-08-15 - Todo manager with interactive and beautiful UI, and vim keybindings.
* [taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) ⭐ 2,109 | 🐛 132 | 🌐 Rust | 📅 2026-08-23 - A terminal user interface for taskwarrior.
* [grit](https://github.com/climech/grit) ⭐ 1,701 | 🐛 19 | 🌐 Go | 📅 2021-09-01 - A multitree-based personal task manager.
* [dstask](https://github.com/naggie/dstask) ⭐ 1,201 | 🐛 43 | 🌐 Go | 📅 2026-05-11 - Single binary terminal-based TODO manager with git-based sync + Markdown notes per task.
* [xit](https://github.com/jotaen/xit) ⭐ 1,121 | 🐛 0 | 📅 2024-01-27 - A plain-text file format for todos and check lists. So, not really a program, but I believe it is worth to list :-)
* [topydo](https://github.com/topydo/topydo) ⭐ 935 | 🐛 82 | 🌐 Python | 📅 2026-03-18 - A powerful todo list application for the console, using the todo.txt format.
* [t](https://github.com/sjl/t) ⭐ 807 | 🐛 10 | 🌐 Python | 📅 2023-10-27 - A command-line todo list manager for people that want to finish tasks, not organize them.
* [Todoman](https://github.com/pimutils/todoman) ⭐ 590 | 🐛 113 | 🌐 Python | 📅 2026-05-25 - A simple, standards-based, CLI todo (aka: task) manager.
* [geek-life](https://github.com/ajaxray/geek-life) ⭐ 562 | 🐛 26 | 🌐 Go | 📅 2026-01-28 - A full-featured TUI task manager.
* [kabmat](https://github.com/PlankCipher/kabmat) ⭐ 425 | 🐛 13 | 🌐 C++ | 📅 2023-01-26 - TUI program for managing kanban boards with vim-like keybindings.
* [kanban-python](https://github.com/Zaloog/kanban-python) ⭐ 348 | 🐛 0 | 🌐 Python | 📅 2026-05-12 - Kanban Terminal App written in Python.
* [omm](https://github.com/dhth/omm) ⭐ 330 | 🐛 11 | 🌐 Go | 📅 2026-08-05 - "on-my-mind" is a keyboard-driven task manager for the command line.
* [Taskline](https://github.com/perryrh0dan/taskline) ⭐ 325 | 🐛 23 | 🌐 TypeScript | 📅 2025-10-31 - Tasks, boards & notes for the command-line habitat.
* [tsk](https://github.com/kakengloh/tsk) ⭐ 250 | 🐛 1 | 🌐 Go | 📅 2022-09-16 - Terminal task management app with an emphasis on simplicity, efficiency and ease of use.
* [td-cli](https://github.com/darrikonn/td-cli) ⭐ 214 | 🐛 11 | 🌐 Python | 📅 2026-04-14 - A command line todo manager, where you can organize and manage your todos across multiple projects.
* [Togo](https://github.com/prime-run/togo) ⭐ 184 | 🐛 6 | 🌐 Go | 📅 2026-06-24 - A fast and simple terminal-based task and todo manager built in go.
* [todocli](https://github.com/HxX2/todocli) ⭐ 155 | 🐛 3 | 🌐 Go | 📅 2025-04-18 - Todo CLI to manage your to do list in a neat way.
* [tascli](https://github.com/Aperocky/tascli) ⭐ 154 | 🐛 0 | 🌐 Rust | 📅 2026-03-23 - A simple, fast, local task and record manager in CLI.
* [mdt](https://github.com/basilioss/mdt) ⭐ 146 | 🐛 3 | 🌐 Shell | 📅 2024-07-31 - A simple command-line Markdown todo list manager inspired by t.
* [judo](https://github.com/giacomopiccinini/judo) ⭐ 117 | 🐛 1 | 🌐 Rust | 📅 2026-02-16 - A multi-database TUI for ToDo lists, using Rust + Ratatui + SQLite.
* [mayhem](https://github.com/BOTbkcd/mayhem) ⭐ 99 | 🐛 0 | 🌐 Go | 📅 2026-03-23 - A minimal TUI based task tracker.
* [TUI Project Manager](https://github.com/NicoDblc/TUI_ProjectManager) ⭐ 34 | 🐛 0 | 🌐 Rust | 📅 2024-03-18 - Simple TUI todo list written in Rust.
* [boards](https://github.com/benrutter/boards) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2023-08-30 - Recursive kanban boards based around the filesystem.
* [CLI-Manager](https://github.com/MikyStar/CLI-Manager) ⭐ 24 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-20 - Command Line Interface for managing tasks locally on the fly.
* [rusk](https://github.com/tagirov/rusk) ⭐ 19 | 🐛 0 | 🌐 Rust | 📅 2026-07-07 - A minimal cross-platform terminal task manager.
* [TODO-CLI-and-TUI](https://github.com/Harsh-bin/TODO-CLI-and-TUI) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2025-05-06 - A small todo app which is both "TUI" and "CLI" based on gum with features like adding tasks for day, week or months, setting target date, adding notes, reward window and many more.
* [FlowStateCLI](https://github.com/sundanc/flowstatecli) ⭐ 12 | 🐛 2 | 🌐 Python | 📅 2025-06-24 - Command-line productivity tool for developers to track work sessions, manage tasks, and set goals + Pomodoro timer (online and offline).
* [wish](https://github.com/levkush/wish) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-03-01 - A delightful wish list manager to keep track of your dreams and desires!
* [cursedtodo](https://github.com/FLchs/cursedtodo) ⭐ 7 | 🐛 3 | 🌐 Python | 📅 2025-02-14 - A minimalist, terminal base todo manager storing tasks as .ics files for storage.
* [td](https://github.com/wolandark/td) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-04-12 - Simple & elegant To Do list manager written In Bash.
* [devtodo](https://swapoff.org/devtodo.html) - A hierarchical command-line task manager, with data storage in JSON format.
* [iKog](https://sites.google.com/site/henspace/ikog/) - A fully-featured task manager encapsulated within a Python script (just carry around the script to retain all the TODOs). When the script is run, a Python shell is opened, where task-related commands can be entered (ADD, LIST, etc.); a pity that commands are uppercase, which requires the annoying use of the Shift key.
* [memo](https://www.byteptr.com/memo/) - Memo is a Unix-style note-taking software for POSIX compatible systems.
* [Redo.vc](https://redo.vc) - Redo.vc is a tool for command line fans that allows you to track your tasks. It is a full-featured todo manager with tagging, projects, recurring tasks and much more, all stored in a JSON file so it is super portable and tooling new apps for the data format is super easy.
* [TaskWarrior](https://taskwarrior.org/) - Todo manager with advanced features, dedicated synchronization server available, many plugins and related tools, healthy software project.
* [todo.txt](http://todotxt.org/) - Minimalistic todo manager that uses a simple plain text file to keep track of items, implemented as a shell script.
* [todo.txt-more](https://git.sr.ht/~proycon/todotxt-more) - Extensions for todo.txt: interactive rofi/fzf control, sync github issues, better colors, time tracking... and more!
* [todoclist](https://github.com/RuslanGagushin/todoclist) - Simple CLI app for check your tasks from todoist.
* [todotxt-machine](https://pypi.org/project/todotxt-machine/) - Interface for todo.txt.
* [TuDu](https://code.meskio.net/tudu/) - Manage hierarchical todos. Each task has a title, a long text description, a deadline (tudu warns you when the date is close), and a scheduled date. There are categories and priorities.
* [Ultralist](https://ultralist.io/) - A simple, powerful, open source task management system for the command line.
* [Yokadi](https://yokadi.github.io/) - Project-based todo manager: every task must be specified with a mandatory project indication. Tasks are stored within a SQLlite DB. Written in Python.

## <a name="time-tracker"></a>Time trackers

Time and habit trackers to measure the amount of time spent on different activities.

* [dijo](https://github.com/NerdyPepper/dijo) ⭐ 2,920 | 🐛 36 | 🌐 Rust | 📅 2024-08-13 - Scriptable, curses-based, digital habit tracker.
* [Watson](https://github.com/TailorDev/Watson) ⭐ 2,538 | 🐛 142 | 🌐 Python | 📅 2025-12-15 - Time tracking CLI to know how much time you are spending on your projects. It can generate nice reports for clients.
* [Timewarrior](https://github.com/GothenburgBitFactory/timewarrior) ⭐ 1,641 | 🐛 125 | 🌐 C++ | 📅 2026-08-22 - A time tracking utility that offers simple stopwatch features as well as sophisticated calendar-based backfill, along with flexible reporting.
* [Timetrap](https://github.com/samg/timetrap) ⭐ 1,512 | 🐛 33 | 🌐 Ruby | 📅 2025-03-12 - A simple command line time tracker written in Ruby. It provides an easy-to-use command line interface for tracking what you spend your time on.
* [arttime](https://github.com/reportaman/arttime) ⭐ 1,378 | 🐛 6 | 🌐 Shell | 📅 2026-08-18 - A feature-rich clock/ timer/ pattern-based time manager in terminal with curated text-art.
* [doing](https://github.com/ttscoff/doing) ⭐ 1,289 | 🐛 2 | 🌐 Ruby | 📅 2026-07-27 - A command line tool for remembering what you were doing and tracking what you've done.
* [Bartib](https://github.com/nikolassv/bartib) ⭐ 844 | 🐛 19 | 🌐 Rust | 📅 2026-03-25 - Easy to use time tracking tool for the command line. It saves a log of all tracked activities as a plain-text file and allows you to create flexible reports.
* [zeit](https://github.com/mrusme/zeit) ⭐ 586 | 🐛 0 | 🌐 Go | 📅 2026-08-23 - A command line tool for tracking time spent on activities.
* [tmux-pomodoro-plus](https://github.com/olimorris/tmux-pomodoro-plus) ⭐ 471 | 🐛 6 | 🌐 Shell | 📅 2025-03-12 - Pomodoro technique into your tmux workflow
* [Moro](https://github.com/getmoro/moro) ⭐ 462 | 🐛 19 | 🌐 TypeScript | 📅 2024-05-01 - A command line tool for tracking work hours, as simple as it can get.
* [habitctl](https://github.com/blinry/habitctl) ⭐ 400 | 🐛 17 | 🌐 Rust | 📅 2024-04-19 - Minimalist command line tool you can use to track and examine your habits.
* [tim:r](https://github.com/sectore/timr) ⭐ 369 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - A TUI for organizing your time: Pomodoro Countdown counter.
* [utt](https://github.com/larose/utt) ⭐ 349 | 🐛 1 | 🌐 Python | 📅 2026-01-08 - Ultimate Time Tracker - A simple command-line time tracker written in Python.
* [hours](https://github.com/dhth/hours) ⭐ 345 | 🐛 16 | 🌐 Go | 📅 2026-08-21 - A no-frills time tracking toolkit for command line nerds.
* [MyTimer](https://github.com/sepandhaghighi/mytimer) ⭐ 148 | 🐛 4 | 🌐 Python | 📅 2026-08-17 - Simple timer for the terminal with timer-mode and alarm.
* [pom](https://github.com/maaslalani/pom) ⭐ 139 | 🐛 5 | 🌐 Go | 📅 2024-05-16 - Pomodoro timer for the terminal.
* [aimssh](https://github.com/sairash/aimssh) ⭐ 65 | 🐛 1 | 🌐 Go | 📅 2026-02-22 - SSH Pomodoro app.
* [Timer-CLI](https://github.com/1Blademaster/timer-cli) ⭐ 61 | 🐛 12 | 🌐 Python | 📅 2026-01-10 - A very simple countdown timer.
* [Productivity Timer](https://github.com/h-sifat/productivity-timer) ⭐ 59 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-15 - A CLI/TUI Pomodoro timer and todo (coming soon) application for keyboard addicts and terminal fans that makes you more productive.
* [yacht](https://github.com/tracyspacy/yacht) ⭐ 29 | 🐛 1 | 🌐 Rust | 📅 2025-03-21 - Yet another command line habit tracker written in Rust.
* [habitmap](https://github.com/shuu-wasseo/habitmap) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2024-04-13 - A command-line app to track your habits and visualise how committed you are to making or maintaining them with colorful heatmaps.
* [MyDoro](https://github.com/Balaji01-4D/my-doro) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2025-12-19 - Modern Pomodoro timer for the terminal (work/break intervals, different themes, and a distraction-free CLI experience).
* [cations](https://github.com/Alcryst/cations) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2024-09-12 - Lightweight, user-friendly habit tracker and productivity tool; terminal-based CLI application.
* [tuicamp](https://github.com/AbeEstrada/tuicamp) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2025-08-18 - Unofficial TimeCamp TUI - seems a time tracker for specific purposes.
* [Hammerclock](https://github.com/itworks99/hammerclock) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2025-05-21 - TUI chess clock and phase tracker application for tabletop games.
* [pomodev](https://github.com/dhruv1710/pomodev) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-06-16 - CLI for Pomodoro timer with built-in Git integration (auot git commit prompt after each work sessions).
* [arbtt](http://arbtt.nomeata.de/) - (automatic, rule-based time tracker) runs in the background, collecting information regarding open windows, focused ones, etc.; it can be configured to display statistics on the collected data, e.g., figuring out the time spent on one specific window.
* [isw](https://gitlab.com/thom-cameron/isw) - A simple terminal stopwatch application for pomodoro etc.
* [Timet](https://frankvielma.github.io/posts/timet-a-powerful-command-line-tool-for-tracking-your-time/) - A lightweight, local time tracker with SQLite storage, offering features like Pomodoro integration, block time and tag distribution plots, detailed statistics, and CSV/iCalendar export.

## <a name="note-taking"></a>Note taking

Tools to take, organize and manage notes.

* [nb](https://github.com/xwmx/nb) ⭐ 8,372 | 🐛 151 | 🌐 Shell | 📅 2026-08-22 - A command line and local web note-taking, bookmarking, archiving, and knowledge base application.
* [jrnl](https://github.com/jrnl-org/jrnl) ⭐ 7,299 | 🐛 150 | 🌐 Python | 📅 2026-08-20 - jrnl is a simple journal application for the command line to easily create, search, and view journal entries; journals are stored as human-readable plain text, and can also be encrypted using AES encryption.
* [kb](https://github.com/gnebbia/kb) ⭐ 3,414 | 🐛 13 | 🌐 Python | 📅 2025-06-21 - A minimalist knowledge base manager.
* [dnote](https://github.com/dnote/dnote) ⭐ 3,069 | 🐛 40 | 🌐 Go | 📅 2026-07-25 - A simple command line notebook for the terminal. It also offers a seamless multi-device sync and a web interface.
* [zk](https://github.com/mickael-menu/zk) ⭐ 2,776 | 🐛 26 | 🌐 Go | 📅 2026-08-24 - zk is a command-line tool helping you to maintain a plain text Zettelkasten or personal wiki.
* [eureka](https://github.com/simeg/eureka) ⭐ 873 | 🐛 8 | 🌐 Rust | 📅 2023-11-04 - Store your ideas without leaving the terminal.
* [TUI-Journal](https://github.com/AmmarAbouZor/tui-journal) ⭐ 774 | 🐛 24 | 🌐 Rust | 📅 2026-08-16 - Terminal-based application written in Rust that allows you to write and manage your journal/notes with a nice user interface.
* [jot](https://github.com/araekiel/jot) ⭐ 610 | 🐛 1 | 🌐 Rust | 📅 2024-01-14 - Jot is a feature-stripped version of Obsidian focused on rapid note management through the terminal. It uses the same format of storage as Obsidian.
* [rucola](https://github.com/Linus-Mussmaecher/rucola) ⭐ 523 | 🐛 2 | 🌐 Rust | 📅 2026-08-24 - Terminal-based markdown note manager.
* [NoteSH](https://github.com/Cvaniak/NoteSH) ⭐ 489 | 🐛 2 | 🌐 Python | 📅 2025-10-05 - Sticky notes App in the Terminal, built with Textual, an amazing TUI framework!
* [sncli](https://github.com/insanum/sncli) ⭐ 430 | 🐛 34 | 🌐 Python | 📅 2025-06-01 - A Python application that gives you access to your Simplenote account via the command line.
* [Captain's Log](https://github.com/NikolaDucak/caps-log) ⭐ 394 | 🐛 16 | 🌐 C++ | 📅 2026-08-14 - A small TUI journaling tool (daily entries saved as md files, tags for organizing entries, browse tags, calendar view, encrypted logs, storage using a git repository).
* [Geeknote](https://github.com/jeffkowalski/geeknote) ⚠️ Archived - A command line client for Evernote that can be use on Linux, FreeBSD and OS X.
* [idea](https://github.com/IonicaBizau/idea) ⭐ 277 | 🐛 2 | 🌐 JavaScript | 📅 2025-02-13 - A lightweight tool for keeping ideas in a safe place quick and easy.
* [dn](https://github.com/tomlockwood/dn) ⭐ 250 | 🐛 1 | 📅 2019-12-15 - Daily notes command line tool.
* [Toney](https://github.com/SourcewareLab/Toney) ⭐ 201 | 🐛 3 | 🌐 Go | 📅 2026-05-27 - A fast, lightweight, terminal-based note-taking TUI app built with Bubbletea; Offers markdown rendering, file navigation and native Neovim editing.
* [note](https://github.com/armand-sauzay/note) ⭐ 194 | 🐛 4 | 🌐 Go | 📅 2025-05-27 - A modern terminal-based note-taking application built with Bubble Tea and Lip Gloss to organize your thoughts with style.
* [cadmus](https://github.com/RyanGreenup/cadmus) ⭐ 172 | 🐛 12 | 🌐 CSS | 📅 2026-06-26 - Shell Scripts to Facilitate Effective Note Taking.
* [FuzPad](https://github.com/JianZcar/FuzPad) ⭐ 164 | 🐛 6 | 🌐 Shell | 📅 2025-11-12 - A minimalistic note management solution, powered by fzf.
* [lazyorg](https://github.com/HubertBel/lazyorg) ⭐ 121 | 🐛 4 | 🌐 Go | 📅 2025-10-03 - Simple terminal-based calendar and note-taking app.
* [tdo](https://github.com/2KAbhishek/tdo) ⭐ 76 | 🐛 0 | 🌐 Shell | 📅 2025-07-21 - Fast and Simple Note Taking.
* [Diary](https://github.com/actuday6418/Diary) ⭐ 73 | 🐛 1 | 🌐 Rust | 📅 2021-06-16 - A diary app written in Rust that encrypts both text and file data, and can decrypt and build a rich HTML representation of your diary when required.
* [meudeus](https://github.com/dj8yfo/meudeus) ⭐ 48 | 🐛 1 | 🌐 Rust | 📅 2024-08-09 - A skim-based `*.md` explore and surf tool.
* [pdiary](https://github.com/manipuladordedados/pdiary) ⭐ 47 | 🐛 2 | 🌐 Python | 📅 2022-09-12 - A simple terminal diary journal application written in Python with encryption support.
* [Noted](https://github.com/torbratsberg/noted) ⭐ 36 | 🐛 1 | 🌐 Go | 📅 2022-10-18 - Notes library, with viewer and shortcuts to add, delete and edit notes.
* [journalC](https://github.com/Dr-42/journalC) ⭐ 17 | 🐛 0 | 🌐 C | 📅 2024-11-13 - A simple encrypted terminal journaling book.
* [note](https://github.com/bdazl/note) ⭐ 12 | 🐛 1 | 🌐 Go | 📅 2024-11-03 - Minimalistic note taking.
* [Standard Unix Notes](https://github.com/Standard-Unix-Notes/unix-notes) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2022-04-28 - GPG Encrypted Notes/Notebook manager for BSD/Linux.
* [tb.go](https://github.com/araaha/tb.go) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2024-08-10 - Tasks, boards & notes for the command-line habitat.
* [posce](https://github.com/vdt/posce) ⭐ 2 | 🐛 0 | 📅 2020-03-24 - A note-taking toolkit for your command line.
* [Clipboard](https://getclipboard.app/) - An easy-to-use information management tool that acts like an external brain.
* [mn](https://github.com/misopog/mn) - A dead simple note-taking script.
* [numen](https://github.com/aguiarsc/numen) - Markdown-compatible AI-Powered Terminal Notepad.
* [Terminal velocity](https://vhp.github.io/terminal_velocity/) - A fast, cross-platform note-taking application for the UNIX terminal.

## <a name="organizers"></a>Organizers and calendars

Calendar and appointment managers.

* [buku](https://github.com/jarun/buku) ⭐ 7,183 | 🐛 6 | 🌐 Python | 📅 2026-08-16 - A powerful bookmark manager written in Python3 and SQLite3.
* [gcalcli](https://github.com/insanum/gcalcli) ⭐ 3,756 | 🐛 170 | 🌐 Python | 📅 2025-10-25 - Access Google Calendars; supports the main tasks: create, delete, and list events.
* [khal](https://github.com/pimutils/khal) ⭐ 3,043 | 🐛 260 | 🌐 Python | 📅 2026-08-24 - Calendar that can synchronize with CalDAV servers through [vdirsyncer](https://github.com/pimutils/vdirsyncer) ⭐ 1,864 | 🐛 222 | 🌐 Python | 📅 2026-08-20.
* [Calcure](https://github.com/anufrievroman/calcure) ⭐ 2,340 | 🐛 8 | 🌐 Python | 📅 2026-06-17 - Modern TUI calendar and task manager with customizable interface.
* [vdirsyncer](https://github.com/pimutils/vdirsyncer) ⭐ 1,864 | 🐛 222 | 🌐 Python | 📅 2026-08-20 - CalDAV synchronization program.
* [tz](https://github.com/oz/tz) ⭐ 898 | 🐛 8 | 🌐 Go | 📅 2025-02-14 - tz helps you schedule things across time zones. It's an interactive TUI program that displays time across the time zones of your choosing.
* [khard](https://github.com/lucc/khard) ⭐ 671 | 🐛 35 | 🌐 Python | 📅 2026-06-20 - vCard address book written in Python. Supports CardDAV.
* [Girok](https://github.com/noisrucer/girok) ⭐ 502 | 🐛 16 | 🌐 Python | 📅 2026-02-07 - A powerful and beautiful CLI scheduler.
* [icsp](https://github.com/loteoo/icsp) ⭐ 146 | 🐛 4 | 🌐 Awk | 📅 2024-07-04 - Command-line iCalendar (.ics) to CSV utility.
* [plann](https://github.com/tobixen/plann) ⭐ 81 | 🐛 9 | 🌐 Python | 📅 2026-08-16 - Command-line interface to online calendars.
* [caldr](https://github.com/mrusme/caldr) ⚠️ Archived - A lightweight CLI / TUI calendar that supports CalDAV.
* [avail](https://github.com/mufeez-amjad/avail) ⭐ 51 | 🐛 1 | 🌐 Rust | 📅 2023-01-09 - Find available times between all your calendars.
* [addrb](https://github.com/mrusme/addrb) ⚠️ Archived - A lightweight CLI / TUI address book that supports CardDAV.
* [pbook](https://github.com/proh14/pbook) ⭐ 31 | 🐛 1 | 🌐 C | 📅 2024-02-20 - A simple phonebook manager for TUI lovers.
* [peroutine](https://github.com/UlyssesZh/peroutine) ⭐ 8 | 🐛 0 | 🌐 Ruby | 📅 2025-08-07 - Remind you of periodical events. The period can be any positive integer of days, so work around the fact that the number of days in a week is prime.
* [calcurse](https://calcurse.org/) - A calendar and scheduling application for the command line. It helps keep track of events, appointments and everyday tasks.
* [goobook](https://gitlab.com/goobook/goobook) - The purpose of GooBook is to make it possible to use your Google Contacts from the command-line and from MUAs such as Mutt. It can be used from Mutt the same way as abook.
* [pal](http://palcal.sourceforge.net/) - Calendar for Unix/Linux systems that can keep track of events; custom, plain text storage format; interesting and fully functional.
* [ppl addressbook](http://ppladdressbook.org/) - Address book tool that uses the vCard format. Built on top of Ruby and Git
* [Remind](https://dianne.skoll.ca/projects/remind/) - Calendar that supports complex rules to define events and used a custom, powerful text-based storage format.
* [remint](https://sr.ht/~mlaparie/remint/) - A simple terminal UI wrapper for D. Skoll's Remind calendar program
* [Wyrd](http://freecode.com/projects/wyrd/) - Curses front-end for [Remind](https://www.roaringpenguin.com/products/remind) written in OCaml with vertically scrollable time-table.

## <a name="financial"></a>Financial tools

Personal ledger trackers, currency converters, and tools to manage and track cryptocurrencies.

* [Ticker](https://github.com/achannarasappa/ticker) ⭐ 6,217 | 🐛 35 | 🌐 Go | 📅 2026-06-28 - Terminal stock watcher and stock position tracker.
* [cointop](https://github.com/cointop-sh/cointop) ⚠️ Archived - A fast and lightweight interactive terminal based UI application for tracking cryptocurrencies.
* [Bagels](https://github.com/EnhancedJax/Bagels) ⭐ 2,884 | 🐛 18 | 🌐 Python | 📅 2025-07-06 - TUI application where you  can track and analyse your money flow.
* [mop](https://github.com/mop-tracker/mop) ⭐ 2,203 | 🐛 6 | 🌐 Go | 📅 2025-12-28 - Stock market tracker for hackers.
* [Invoice](https://github.com/maaslalani/invoice) ⭐ 2,191 | 🐛 25 | 🌐 Go | 📅 2024-06-18 - Generate invoices from the command line.
* [Puffin](https://github.com/siddhantac/puffin) ⭐ 567 | 🐛 11 | 🌐 Go | 📅 2026-03-11 - A beautiful TUI dashboard for hledger.
* [cash-cli](https://github.com/xxczaki/cash-cli) ⭐ 266 | 🐛 16 | 🌐 JavaScript | 📅 2026-04-30 - Convert Currency Rates.
* [budget\_tracker\_tui](https://github.com/Feromond/budget_tracker_tui) ⭐ 260 | 🐛 11 | 🌐 Rust | 📅 2026-08-05 - A simple TUI budget tracker app built in rust. Designed to track income and expenses and help visualize and gather basic insights from your transactions.
* [abandon](https://github.com/hrj/abandon) ⭐ 185 | 🐛 32 | 🌐 Scala | 📅 2026-08-24 - A text based, double-entry accounting system inspired by Ledger with infinite precision arithmetic. Made in Java. Includes a GUI.
* [stocksTUI](https://github.com/andriy-git/stocksTUI) ⭐ 158 | 🐛 2 | 🌐 Python | 📅 2026-07-09 - StocksTUI: Real-time stock market data in your terminal.
* [moeda](https://github.com/thompsonemerson/moeda) ⭐ 149 | 🐛 6 | 🌐 JavaScript | 📅 2023-06-25 - A foreign exchange rates and currency conversion using the command line.
* [Lakshmi](https://github.com/sarvjeets/lakshmi) ⭐ 148 | 🐛 0 | 🌐 Python | 📅 2026-08-18 - Investing library and command-line interface inspired by the Bogleheads philosophy.
* [portfolio\_rs](https://github.com/MarkusZoppelt/portfolio_rs) ⭐ 91 | 🐛 3 | 🌐 Rust | 📅 2026-08-24 - A command line TUI tool for managing financial investment portfolios.
* [gocost](https://github.com/madalinpopa/gocost) ⭐ 64 | 🐛 4 | 🌐 Go | 📅 2026-06-02 - Simple TUI application to manage monthly expenses; Built with Go and Bubble Tea framework.
* [Finance Tracker](https://github.com/shen-kit/finance-tracker-tui/) ⭐ 35 | 🐛 3 | 🌐 Go | 📅 2025-02-26 - TUI financial tracker written in Go, using sqlite database.
* [Quoter](https://github.com/frossm/quoter) ⭐ 23 | 🐛 1 | 🌐 Java | 📅 2024-03-20 - The console based stock quote tool.
* [Cloudcash](https://github.com/mrusme/cloudcash) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2026-07-21 - Check your cloud spending from the CLI, from Waybar, and from the macOS menu bar!
* [bits](https://github.com/jtraub91/bits) ⭐ 6 | 🐛 15 | 🌐 Python | 📅 2025-08-17 - CLI tool and pure Python library for Bitcoin.
* [ecb-rates](https://github.com/lov3b/ecb-rates) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-12-17 - Fetch exchage rates from the European Central Bank.
* [paycon](https://github.com/arcorion/paycon) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-01-22 - Converts pay amounts between different time units.
* [beancount](https://beancount.github.io/) - Double-entry bookkeeping computer language that lets you define financial transaction records in a text file, read them in memory, generate a variety of reports from them, and provides a web interface.
* [budget-cli](https://www.joshcanhelp.com/budget-cli/) - Import, de-dupe, categorize, and report on financial transactions.
* [hledger](https://hledger.org/) - A is fast, reliable, free, multicurrency double-entry accounting software to track money, investments, cryptocurrencies, time, or any other quantifiable commodity; uses a future-proof plain text file format.
* [ledger](http://ledger-cli.org/) - A powerful, double-entry accounting system; it uses a simple yet powerful text syntax to specify the items to account.
* [rustledger](https://rustledger.github.io) - Pure Rust implementation of Beancount, a drop-in replacement that is 10x faster with a single binary and no dependencies.

# <a name="Productivity"></a>Productivity

## <a name="ai"></a>AI / LLM integration

Interfaces and front-ends to LLM engines and other tools powered by artificial intelligence and Natural Language Processing.

* [Gemini CLI](https://github.com/google-gemini/gemini-cli) ⭐ 106,663 | 🐛 854 | 🌐 TypeScript | 📅 2026-08-25 - It provides lightweight access to Gemini from the terminal.
* [fabric](https://github.com/danielmiessler/fabric) ⭐ 43,519 | 🐛 65 | 🌐 Go | 📅 2026-08-09 - An open-source framework for augmenting humans using AI, providing a modular framework for solving specific problems using a crowdsourced set of AI prompts that can be used anywhere.
* [AIChat](https://github.com/sigoden/aichat) ⭐ 10,392 | 🐛 98 | 🌐 Rust | 📅 2026-02-23 - Using ChatGPT/GPT-3.5/GPT-4 in the terminal.
* [Mods!](https://github.com/charmbracelet/mods) ⚠️ Archived - AI for the command line, built for pipelines.
* [Chatblade](https://github.com/npiv/chatblade) ⭐ 2,591 | 🐛 20 | 🌐 Python | 📅 2026-02-02 - Chatblade is a versatile command-line interface (CLI) tool designed to interact with OpenAI's ChatGPT.
* [Elia](https://github.com/darrenburns/elia) ⭐ 2,482 | 🐛 25 | 🌐 Python | 📅 2024-10-10 - A terminal ChatGPT client built with Textual.
* [tenere](https://github.com/pythops/tenere) ⭐ 680 | 🐛 10 | 🌐 Rust | 📅 2026-05-10 - A TUI for LLMs (ChatGPT, llama\_cpp, ollama) written in Rust.
* [Ferrules](https://github.com/aminediro/ferrules) ⭐ 612 | 🐛 12 | 🌐 C | 📅 2026-04-26 - Modern, fast, document parser written in Rust designed to generate LLM-ready documents.
* [parllama](https://github.com/paulrobello/parllama) ⭐ 487 | 🐛 4 | 🌐 Python | 📅 2026-07-11 - TUI designed for easy management and use of Ollama based LLMs.
* [savvy-cli](https://github.com/getsavvyinc/savvy-cli) ⭐ 464 | 🐛 0 | 🌐 Go | 📅 2025-01-28 - Automatically capture and surface your team's tribal knowledge.
* [termite](https://github.com/shobrook/termite) ⭐ 419 | 🐛 7 | 🌐 Python | 📅 2025-01-06 - Generative UI in your terminal.
* [leettools](https://github.com/leettools-dev/leettools) ⭐ 343 | 🐛 10 | 🌐 Python | 📅 2026-04-19 - AI Search tools.
* [kwaak](https://github.com/bosun-ai/kwaak) ⭐ 331 | 🐛 33 | 🌐 Rust | 📅 2026-01-27 - Run a team of autonomous AI agents on your code.
* [Instrukt](https://github.com/blob42/Instrukt) ⭐ 330 | 🐛 6 | 🌐 Python | 📅 2025-05-14 - A integrated AI environment in the terminal. Build, test and instruct agents.
* [ata](https://github.com/transformrs/ata) ⭐ 285 | 🐛 9 | 🌐 Rust | 📅 2025-04-01 - Ask the Terminal Anything: OpenAI GPT in the terminal.
* [ChatGPTerminator](https://github.com/AineeJames/ChatGPTerminator) ⚠️ Archived - GPTerminator provides a convenient way to interact with OpenAI's chat completion and image generation API's using your command line interface.
* [gemini-cli](https://github.com/reugn/gemini-cli) ⭐ 219 | 🐛 3 | 🌐 Go | 📅 2025-11-22 - A command-line interface (CLI) for Google Gemini.
* [cai](https://github.com/ad-si/cai) ⭐ 202 | 🐛 6 | 🌐 Rust | 📅 2026-08-24 - The fastest CLI tool for prompting LLMs. Including support for prompting several LLMs at once!
* [clevercli](https://github.com/clevercli/clevercli) ⚠️ Archived - ChatGPT powered CLI utilities. Easily add new prompt types.
* [hns](https://github.com/primaprashant/hns) ⭐ 116 | 🐛 4 | 🌐 Python | 📅 2026-07-21 - A privacy-focused open-source command-line tool for on-device speech-to-text. It records your voice, transcribes it completely locally using faster-whisper, and automatically copies the text to clipboard for immediate use in any application.
* [unibear](https://github.com/kamilmac/unibear) ⭐ 113 | 🐛 9 | 🌐 TypeScript | 📅 2025-06-10 - A lean TUI AI assistant.
* [AI](https://github.com/nitefood/ai-bash-gpt) ⭐ 85 | 🐛 0 | 🌐 Shell | 📅 2025-08-15 - A command-line ChatGPT client in BASH with conversation/completion support.
* [OrChat](https://github.com/oop7/OrChat) ⭐ 81 | 🐛 0 | 🌐 Python | 📅 2026-02-15 - A powerful, feature-rich command-line interface for interacting with AI models through OpenRouter.
* [cha](https://github.com/MehmetMHY/cha) ⚠️ Archived - A simple CLI chat tool to easily interface with OpenAI's models.
* [Elroy](https://github.com/elroy-bot/elroy) ⭐ 59 | 🐛 16 | 🌐 Python | 📅 2026-06-03 - AI personal assistant that remembers and sets goals.
* [Context Extractor](https://github.com/vaibhav-mattoo/cxt) ⭐ 52 | 🐛 1 | 🌐 Rust | 📅 2026-07-27 - Command line tool that aggregates file and directory contents into the clipboard, for providing project context to AI chatbots in the browser like ChatGPT and Perplexity.
* [Browser CLI](https://github.com/browsemake/browser-cli) ⭐ 46 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-23 - AI agent browser automation tool.
* [safespace](https://github.com/danlou/safespace) ⭐ 38 | 🐛 3 | 🌐 Python | 📅 2023-09-22 - Your local AI counselor. LLM app that runs offline from a single binary.
* [Alibaba-CLI-Scraper](https://github.com/poneoneo/Alibaba-CLI-Scraper) ⚠️ Archived - Create your own Alibaba dataset and interact with it in plain English.
* [llm-term](https://github.com/juftin/llm-term) ⭐ 32 | 🐛 4 | 🌐 Python | 📅 2025-01-07 - Chat with OpenAI's GPT models directly from the command line.
* [genie](https://github.com/harshalranjhani/genie) ⭐ 31 | 🐛 2 | 🌐 Go | 📅 2025-12-03 - Personal assistant for the CLI that helps in tasks such as running commands, generating images and music, summarizing comments.
* [gpterm](https://github.com/MakisChristou/gpterm) ⭐ 31 | 🐛 0 | 🌐 Rust | 📅 2023-08-04 - Yet another command-line ChatGPT frontend written in Rust.
* [bookworm](https://github.com/kiran94/bookworm) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2025-01-04 - LLM-powered bookmark search engine.
* [mcp-manager](https://github.com/nstebbins/mcp-manager) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2025-04-23 - CLI tool for managing Model Context Protocol (MCP) servers in one place & using them across them different clients.
* [HAL 2023](https://github.com/Brutuski/hal2023-cli) ⭐ 19 | 🐛 2 | 🌐 Shell | 📅 2023-04-24 - Inspired by the infamous HAL9000, it is a simple script to chat with OpenAI's ChatGPT.
* [chat.sh](https://github.com/basherbots/chat.sh) ⭐ 15 | 🐛 2 | 🌐 Shell | 📅 2024-10-02 - Pipeable LLM wrapper with code execution (OpenRouter).
* [codepack v4](https://github.com/w3spi5/codepack) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2026-07-01 - CLI tool to extract folder structure and file contents with advanced minification for AI processing.
* [CarthageAI](https://github.com/alaadotcom/CarthageAI) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2025-06-29 - Multi-provider AI terminal assistant for developers and AI enthusiasts.
* [GPTparser](https://github.com/dtflare/GPTparser) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2024-04-02 - Use GPTparser with your OpenAI API to scrape & parse files into structured JSON files.
* [chatgpt](https://github.com/mglantz/chatgpt) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2023-01-23 - Simple command line integration to ChatGPT.
* [AskOra](https://github.com/rosettadb/askora) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2025-08-14 - Unified Python CLI interacting with multiple AI providers sending prompts and getting structured AI responses, all from your terminal.
* [egit](https://github.com/Sweet-Papa-Technologies/egit) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2025-10-31 - A.I. tools and workflows for Git.
* [LamaCLI](https://github.com/hariharen9/lamacli) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2026-03-01 - AI assistante in both interactive mode and command-line mode in the terminal.
* [wtg](https://github.com/brylee10/wtg) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2025-02-13 - What The GPT (wtg), a CLI to chat with your program logs.
* [cligpt](https://github.com/paij0se/cligpt) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2024-02-27 - ChatGPT but in the terminal.
* [clai](https://github.com/iivvoo/clai) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2024-01-18 - Command Line AI is a command line integration for openai. It's setup to help you learn new shell commands and construct more complex commands.
* [ollama](https://ollama.com/) - Get up and running with large language models locally.
* [vibebox](https://vibebox.robcholz.com) - Per-project micro-VM sandbox for running coding agents on macOS with fast re-entry and explicit mounts.

## <a name="productivity"></a>Productivity

Applications for improving own productivity that do not deserve (at the moment) a specific category; e.g., resume generators and mind maps.

* [wtf](https://github.com/wtfutil/wtf) ⭐ 17,061 | 🐛 102 | 🌐 Go | 📅 2026-08-05 - The personal information dashboard for your terminal, including todos, calendar, JIRA, etc.
* [h-m-m](https://github.com/nadrad/h-m-m) ⭐ 2,284 | 🐛 4 | 🌐 PHP | 📅 2026-07-06 - h-m-m (pronounced like the interjection "hmm") is a simple, fast, keyboard-centric terminal-based tool for working with mind maps.
* [tuxi](https://github.com/Bugswriter/tuxi) ⚠️ Archived - A CLI tool that scrapes Google search results and SERPs that provides instant and concise answers.
* [speedread](https://github.com/pasky/speedread) ⭐ 1,257 | 🐛 13 | 🌐 Perl | 📅 2024-06-11 - A simple terminal-based open source Spritz-alike filter that shows input text as a per-word RSVP (rapid serial visual presentation) aligned on optimal reading points.
* [Sinkzone](https://github.com/berbyte/sinkzone) ⭐ 345 | 🐛 4 | 🌐 Go | 📅 2026-08-24 - Application that blocks everything by default unless you explicitly allow it; A DNS tool for productivity, focus, and child safety.
* [gtt](https://github.com/eeeXun/gtt) ⭐ 307 | 🐛 2 | 🌐 Go | 📅 2026-08-02 - Google Translate TUI (Originally), now supporting Apertium, Argos, Bing, ChatGPT, DeepL, DeepLX, Google, Reverso.
* [telert](https://github.com/navig-me/telert) ⭐ 287 | 🐛 8 | 🌐 Python | 📅 2026-08-07 - Lightweight CLI and Python utility that sends alerts (Telegram, Slack, Teams, Desktop, Audio) when commands complete.
* [ancv](https://github.com/alexpovel/ancv) ⭐ 269 | 🐛 3 | 🌐 Python | 📅 2026-08-04 - Renders your (JSON) resume/CV for online & pretty terminal display.
* [DDQA](https://github.com/DataDog/ddqa) ⭐ 109 | 🐛 1 | 🌐 Python | 📅 2026-08-21 - Jira TUI to help with software releasestool for users of Jira to perform QA of anticipated releases of code on GitHub.
* [multranslate](https://github.com/Lifailon/multranslate) ⭐ 62 | 🐛 1 | 🌐 JavaScript | 📅 2025-03-31 - A TUI for translating text in multiple translators simultaneously, with support for translation history and language detection.
* [hnjobs](https://github.com/mwinters0/hnjobs) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2025-09-10 - Console tool to find the best match on Who's Hiring.
* [Git-Gamify](https://github.com/DeerYang/git-gamify) ⭐ 24 | 🐛 2 | 🌐 Python | 📅 2026-03-13 - A command-line tool that turns your Git workflow into a fun RPG loop where you cand earn XP, level up and unlock achievements from real Git usage.
* [floww](https://github.com/dagimg-dot/floww) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2026-08-01 - Streamline your workflow setup on Linux desktops, defining workspace layouts and application sets in simple configuration files and automate the process of switching workspaces and launching applications.
* [gdir](https://github.com/pafoster/gdir) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2022-12-19 - A command line tool which queries Google Directions. The tool displays results as human-readable text.
* [classis](https://github.com/ginschel/classis) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2023-07-31 - An easy CLI for the terminal fans out there who want to access Open Assistant's API through the terminal or want to use the API in their own applications.
* [zeitkatze](https://github.com/leonmavr/zeitkatze) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2022-03-10 - Simplest stopwatch in a Linux console.
* [autolog](https://github.com/daveymoores/autolog) ⭐ 3 | 🐛 5 | 🌐 Rust | 📅 2026-04-23 - Git-based CLI tool for timesheet generation.
* [Profile Fox](https://github.com/talwrii/profile-fox) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-03-01 - Opens new tabs in a specific firefox profile.
* [try-rs](https://try-rs.org) - Temporary workspace manager with a TUI to organize, navigate, and manage experiments and throwaway projects.

## <a name="office"></a>Office tools

Programs to manage spreadsheets and to make presentations.

* [Slides](https://github.com/maaslalani/slides) ⭐ 11,628 | 🐛 77 | 🌐 Go | 📅 2026-07-08 - Terminal based presentation tool.
* [presenterm](https://github.com/mfontanini/presenterm) ⭐ 8,790 | 🐛 75 | 🌐 Rust | 📅 2026-05-22 - A terminal slideshow tool.
* [sc-im](https://github.com/andmarti1424/sc-im) ⭐ 5,689 | 🐛 118 | 🌐 C | 📅 2026-08-06 - (Spreadsheet Calculator Improvised) - an `ncurses` spreadsheet program for terminal. It is rich in functionalities, but the syntax of functions and other details are different from the common spreadsheets such as Excel and Calc, making difficult to "re-cycle" existing knowledge on these programs to work proficiently with sc-im. Nevertheless, a nice piece of software."
* [qpdf](https://github.com/qpdf/qpdf) ⭐ 5,347 | 🐛 172 | 🌐 C++ | 📅 2026-08-22 - QPDF: A content-preserving PDF document transformer that allows performing several types of operations on PDF files, such as splitting, merging, etc.
* [mdp](https://github.com/visit1985/mdp) ⭐ 5,275 | 🐛 12 | 🌐 C | 📅 2025-07-09 - A command-line based Markdown presentation tool.
* [WOPR](https://github.com/yaronn/wopr) ⭐ 3,086 | 🐛 7 | 🌐 JavaScript | 📅 2024-04-01 - A simple markup language for creating rich terminal reports, presentations, and infographic.
* [patat](https://github.com/jaspervdj/patat) ⭐ 2,740 | 🐛 23 | 🌐 Haskell | 📅 2026-06-25 - Terminal-based presentations using Pandoc.
* [DeckTape](https://github.com/astefanutti/decktape) ⭐ 2,422 | 🐛 50 | 🌐 JavaScript | 📅 2026-07-13 - DeckTape is a high-quality PDF exporter for HTML presentation frameworks.
* [Lotus 1-2-3 for Linux](https://github.com/taviso/123elf) ⭐ 1,284 | 🐛 40 | 🌐 C | 📅 2026-06-27 - A native port of Lotus 1-2-3 Release 3 to Linux.
* [tuitorial](https://github.com/basnijholt/tuitorial) ⭐ 529 | 🐛 15 | 🌐 Python | 📅 2026-08-24 - Create beautiful terminal-based code tutorials with syntax highlighting and interactive navigation.
* [pysentation](https://github.com/mimseyedi/pysentation) ⭐ 262 | 🐛 2 | 🌐 Python | 📅 2025-03-18 - pysentation is a CLI for displaying Python presentations.
* [SheetsUI](https://github.com/zaphar/sheetsui) ⭐ 246 | 🐛 3 | 🌐 Rust | 📅 2026-03-03 - A console based (TUI) spreadsheet application.
* [SSH-Slides](https://github.com/ivantsepp/ssh-slides) ⭐ 135 | 🐛 0 | 🌐 Go | 📅 2023-07-10 - SSH server that hosts terminal-based presentations where your viewers can follow along in their own terminals.
* [tui-slides](https://github.com/Chleba/tui-slides) ⭐ 83 | 🐛 2 | 🌐 Rust | 📅 2024-09-12 - TerminalpPresentation program with modern TUI.
* [Slideck](https://github.com/piotrmurach/slideck) ⭐ 54 | 🐛 1 | 🌐 Ruby | 📅 2025-03-30 - Present Markdown-powered slide decks in the terminal.
* [bashform](https://github.com/devmegablaster/bashform) ⭐ 49 | 🐛 3 | 🌐 Go | 📅 2024-12-28 - Create and share forms in the terminal over SSH.
* [PDFjuicer](https://github.com/dmikhr/pdfjuicer) ⭐ 44 | 🐛 0 | 🌐 Go | 📅 2025-11-09 - CLI tool for converting PDF pages to high-quality images. It features custom image sizing, scaling options, thumbnail generation, and batch processing.
* [ggl](https://github.com/taraqfarhan/ggl) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-08-04 - Search the web (google, youtube, gmail, wiki, github, stackoverflow), prompt to send emails, prompt chatGPT, Gemini right from the terminal (command line).
* [gpa-calculator](https://github.com/kitesi/gpa-calculator) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2025-07-20 - GPA calculator CLI app that stores data in local files; written in Go.
* [PDFtk](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/) - PDFtk is a simple tool for doing everyday things with PDF documents.
* [sent](https://tools.suckless.org/sent/) - Simple plain-text presentation tool.
* [Teapot](https://www.syntax-k.de/projekte/teapot/) - Compact ncurses-based spreadsheet with original syntax, 3D-style and built-in functions.
* [tpp](http://www.ngolde.de/tpp.html) - (text presentation program) - a ncurses Ruby program that allows producing nice text-based presentation with simple markup language.

## <a name="writing"></a>Writing

Tools to assist the writing of text and documents, including translation, spell checking, etc..

* [alex](https://github.com/get-alex/alex) ⭐ 5,100 | 🐛 28 | 🌐 JavaScript | 📅 2024-11-27 - Catch insensitive, inconsiderate writing, by finding gender favoring, polarizing, race related, or other unequal phrasing in text.
* [write good](https://github.com/btford/write-good) ⭐ 5,086 | 🐛 24 | 🌐 JavaScript | 📅 2025-03-10 - Naive linter for English prose.
* [sdcv](https://github.com/Dushistov/sdcv) ⭐ 365 | 🐛 43 | 🌐 C++ | 📅 2025-12-17 - Simple, cross-platform, text-based utility for working with dictionaries in StarDict format.
* [GTT - Google Translate TUI](https://github.com/eeeXun/GTT) ⭐ 307 | 🐛 2 | 🌐 Go | 📅 2026-08-02 - A TUI interface to bring Google Translation in the terminal.
* [storycraftr](https://github.com/raestrada/storycraftr) ⭐ 162 | 🐛 14 | 🌐 Python | 📅 2026-03-06 - StoryCraftr is an open-source AI-powered tool that helps writers craft stories, generate worldbuilding details, and create book outlines and chapters seamlessly through a simple CLI. Empower your creativity with AI.
* [trino](https://github.com/eneserdogan/trino) ⭐ 144 | 🐛 2 | 🌐 JavaScript | 📅 2022-12-06 - Quick and easy translation of words and phrases entered in the command line.
* [VocabCLI](https://github.com/HighnessAtharva/VocabCLI) ⭐ 69 | 🐛 0 | 🌐 Python | 📅 2026-07-22 - Lightweight CLI that allows users to look up word definitions, examples, synonyms, and antonyms directly via the command line; it also offers advanced Text Classification and Processing via the use of Natural Language Processing and Machine Learning algorithms.
* [cambd-cli](https://github.com/rocktimsaikia/cambd) ⭐ 36 | 🐛 2 | 🌐 Python | 📅 2026-08-08 - A CLI tool to automate the process to access the Cambridge dictionary.
* [Grammatical](https://github.com/pncnmnp/grammatical) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2023-03-20 - Corrects the spelling and grammar of your text using ChatGPT.
* [rdict](https://github.com/Lodobo/rdict) ⭐ 22 | 🐛 2 | 🌐 Rust | 📅 2024-11-27 - Offline dictionary using data from wiktionary written in Rust.
* [gdict](https://github.com/Lodobo/gdict) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2023-08-19 - An offline CLI dictionary written in go, using data from wiktionary.
* [Translate Shell](https://www.soimort.org/translate-shell/) - Translator using Google Translate, Bing Translator, Yandex.Translate, etc.

## <a name="calc"></a>Calculators

Calculators for mathematical operations among numbers, dates, base conversions, etc..

* [Numbat](https://github.com/sharkdp/numbat) ⭐ 2,664 | 🐛 106 | 🌐 Rust | 📅 2026-08-23 - Numbat is a calculator for scientific computations with first class support for physical dimensions and units.
* [kalker](https://github.com/PaddiM8/kalker) ⭐ 1,910 | 🐛 40 | 🌐 Rust | 📅 2026-07-10 - Calculator that supports math-like syntax with user-defined variables, functions, derivation, integration, and complex numbers.
* [Bitwise](https://github.com/mellowcandle/bitwise) ⭐ 720 | 🐛 12 | 🌐 C | 📅 2026-08-22 - Base conversion and bit manipulator in ncurses.
* [bcal](https://github.com/jarun/bcal) ⭐ 699 | 🐛 0 | 🌐 C | 📅 2026-08-16 - Byte CALculator - A REPL CLI utility for storage expression evaluation, SI/IEC conversion, byte address calculation, base conversion and LBA/CHS calculation.
* [Programmer calculator](https://github.com/alt-romes/programmer-calculator) ⭐ 589 | 🐛 5 | 🌐 C | 📅 2025-11-06 - Terminal calculator made for programmers working with multiple number representations, sizes, and overall close to the bits.
* [pdd](https://github.com/jarun/pdd) ⭐ 406 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - Tiny date, time diff calculator.
* [kalc](https://github.com/bgkillas/kalc) ⭐ 232 | 🐛 0 | 🌐 Rust | 📅 2026-01-25 - A complex numbers, 2D/3D graphing, arbitrary precision, vector, CLI calculator with real-time output.
* [mdlt](https://github.com/metadelta/mdlt) ⭐ 197 | 🐛 4 | 🌐 JavaScript | 📅 2017-11-01 - A lightweight command line tool that lets you perform arithmetic and symbolic math operations right from the terminal.
* [CalcPy](https://github.com/idanpa/calcpy) ⭐ 117 | 🐛 2 | 🌐 Python | 📅 2026-01-17 - Terminal calculator and advanced math solver using Python, IPython and SymPy.
* [DateTimeMate](https://github.com/jftuga/DateTimeMate) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2026-07-18 - Golang package and CLI to compute the difference between date, time or duration.
* [Vectro](https://github.com/gurgeous/vectro) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2025-03-12 - RPN (reversible polish notation) calculator for your terminal.
* [AngouriMathCLI](https://github.com/asc-community/AngouriMathCLI) ⭐ 19 | 🐛 5 | 🌐 C# | 📅 2024-11-24 - CLI calculator based on AngouriMath.
* [genius](https://github.com/GNOME/genius) ⭐ 11 | 🐛 0 | 🌐 HTML | 📅 2026-04-01 - Genius calculator is a general purpose calculator and mathematics tool with many features.
* [HIP35](https://github.com/leonmavr/HIP35) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2024-06-17 - HP-35 RPN calculator emulator in C++17 with a terminal user interface.
* [ka](https://github.com/Kevinpgalligan/ka) ⭐ 7 | 🐛 6 | 🌐 Python | 📅 2025-06-19 - A calculator language.
* [numio-cli](https://github.com/neholos/numio-cli) ⭐ 6 | 🐛 11 | 🌐 Swift | 📅 2025-03-16 - Tool to perform time calculations.
* [TuringTape](https://github.com/cmspeedrunner/TuringTape) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2025-02-24 - Turing machine.
* [maxima](https://maxima.sourceforge.io/) - Maxima is a manipulation system for symbolic and numerical expressions, including differentiation, integration, Taylor series, Laplace transforms, ordinary differential equations, systems of linear equations, polynomials, sets, lists, vectors, matrices and tensors.
* [Nota](https://kary.us/nota/) - Terminal calculator with rich notation.
* [Qalculate](https://qalculate.github.io/) - Multi-purpose calculator with customizable functions, units, arbitrary precision, plotting (it includes a GUI).
* [Speedcrunch](https://heldercorreia.bitbucket.io/speedcrunch) - SpeedCrunch is a high-precision scientific calculator featuring a fast, keyboard-driven user interface.

## <a name="pastebin"></a>Pastebin

Services that allows online sharing of text and other content.

* [GoCatGo](https://github.com/vaaleyard/gocatgo) ⚠️ Archived - GoCatGo is another pastebin tool with a super focus on transparency.
* [feuille](https://basedwa.re/tmtt/feuille.git) - A fast, dead-simple socket-based pastebin.

## <a name="cheatsheet"></a>Commands cheatsheet and snippets

Tools to manage often used commands, code snippets, and alternative manual pages.

* [The Fuck](https://github.com/nvbn/thefuck) ⭐ 97,744 | 🐛 455 | 🌐 Python | 📅 2024-07-19 - Magnificent app which corrects your previous console command (although I would be extra-cautious at making a program to automatically infer what I was intending).
* [navi](https://github.com/denisidoro/navi) ⭐ 17,474 | 🐛 113 | 🌐 Rust | 📅 2026-07-28 - An interactive cheatsheet tool for the command-line.
* [tealdeer](https://github.com/dbrgn/tealdeer) ⭐ 6,457 | 🐛 14 | 🌐 Rust | 📅 2026-08-24 - Very fast implementation of tldr in Rust.
* [pet](https://github.com/knqyf263/pet) ⭐ 5,334 | 🐛 29 | 🌐 Go | 📅 2026-03-13 - Pet is a simple command-line snippet manager, written in Go.
* [Nap](https://github.com/maaslalani/nap) ⭐ 2,219 | 🐛 17 | 🌐 Go | 📅 2024-05-18 - Code snippet manager that allows creating and access new snippets quickly with the command-line interface or browse, manage, and organize them with the text-user interface.
* [eg](https://github.com/srsudar/eg) ⭐ 2,040 | 🐛 15 | 🌐 Python | 📅 2025-02-06 - Useful examples at the command line.
* [carapace](https://github.com/rsteube/carapace-bin) ⭐ 1,933 | 🐛 102 | 🌐 Go | 📅 2026-08-24 - Carapace provides argument completion for multiple CLI commands and works across multiple POSIX and non-POSIX shells.
* [IntelliShell](https://github.com/lasantosr/intelli-shell) ⭐ 1,277 | 🐛 6 | 🌐 Rust | 📅 2026-07-26 - Command template and snippet manager for the shell. Like IntelliSense, but for shells, acting like a bookmark store for commands.
* [halp](https://github.com/orhun/halp) ⭐ 763 | 🐛 5 | 🌐 Rust | 📅 2026-08-01 - halp aims to help find the correct arguments for command-line tools by checking the predefined list of commonly used options/flags.
* [Wat](https://github.com/dthree/wat) ⭐ 509 | 🐛 18 | 🌐 JavaScript | 📅 2016-09-18 - Instant, central, community-built docs.
* [gocheat](https://github.com/Achno/gocheat) ⭐ 341 | 🐛 8 | 🌐 Go | 📅 2025-10-26 - Customizable TUI cheatsheet for keybindings, hotkeys, gestures and aliases.
* [docfd](https://github.com/darrenldl/docfd) ⭐ 288 | 🐛 4 | 🌐 OCaml | 📅 2026-08-21 - TUI fuzzy document finder that looks for documentation files in Markdown and txt format in the directory tree.
* [bkmr](https://github.com/sysid/bkmr) ⭐ 263 | 🐛 0 | 🌐 Rust | 📅 2026-07-12 - A unified CLI tool for bookmark, snippet, and knowledge management.
* [MUC](https://github.com/nate-sys/muc) ⚠️ Archived - Visualize your most used commands.
* [cheatshh](https://github.com/AnirudhG07/cheatshh) ⭐ 190 | 🐛 0 | 🌐 Shell | 📅 2025-08-15 - A fzf based cheatsheet to store commands and their descriptions in a place you can look into so you dont have to remember them.
* [tome](https://github.com/laktak/tome) ⭐ 175 | 🐛 0 | 🌐 Vim Script | 📅 2026-08-22 - Interactive Script playbooks for your terminal with Vim/Neovim (and Tmux).
* [snipt](https://github.com/snipt/snipt) ⭐ 149 | 🐛 5 | 🌐 Rust | 📅 2026-04-02 - Snipt is a powerful text snippet expansion tool.
* [alman](https://github.com/vaibhav-mattoo/alman) ⭐ 92 | 🐛 3 | 🌐 Rust | 📅 2026-08-24 - TUI for managing shell aliases with intelligent suggestions based on you command history (organize, create and manage aliases across multiple files and shells).
* [ehh](https://github.com/lennardv2/ehh) ⭐ 81 | 🐛 0 | 🌐 Python | 📅 2022-08-22 - Command-line tool for remembering Linux/terminal commands.
* [snip](https://github.com/mehran-prs/snip) ⭐ 80 | 🐛 0 | 🌐 Go | 📅 2025-02-11 - A simple and minimal command-line snippet manager.
* [fzf-help](https://github.com/BartSte/fzf-help) ⭐ 60 | 🐛 3 | 🌐 Shell | 📅 2026-08-20 - An fzf extension that allows you to select command line options of a given command; the options are retrieved from the command its `--help` documentation.
* [cmdCompass](https://github.com/johnwangwyx/cmdCompass) ⭐ 59 | 🐛 3 | 🌐 Python | 📅 2024-10-26 - Cross-platform terminal command manager/notebook with features like custom collections, tagging, variable substitution, and integrated man page with option highlighting.
* [topalias](https://github.com/meteoritt/topalias) ⭐ 55 | 🐛 16 | 🌐 HTML | 📅 2026-01-29 - Linux alias generator from bash/zsh command history with statistics, written on Python.
* [snip](https://github.com/marcopaganini/snip) ⭐ 37 | 🐛 0 | 🌐 Shell | 📅 2024-11-17 - A snippet manager for bash, mostly written in pure bash.
* [ManPDF & ManWEB](https://github.com/sebastiancarlos/manpdf) ⭐ 36 | 🐛 2 | 🌐 Shell | 📅 2024-04-19 - Read your Man pages in PDF format. Even online!
* [kmdr-cli](https://github.com/ediardo/kmdr-cli) ⭐ 21 | 🐛 0 | 📅 2022-02-27 - The CLI tool for explaining commands from your terminal.
* [rsnip](https://github.com/sysid/rsnip) ⚠️ Archived - A powerful command-line snippet manager.
* [asciit](https://github.com/Q1CHENL/asciit) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2025-04-21 - A more compact and intuitive ASCII table in your terminal: an alternative to "man 7 ascii" and "ascii".
* [Subshella](https://github.com/danpizz/subshella) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2025-07-10 - The program helps you manage groups of Bash environment variables with an interactive menu, making it quick to activate different configurations.
* [mdpick](https://github.com/toolleeo/mdpick) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-04-03 - A terminal user interface (TUI) tool for interactively selecting and extracting code blocks or links from Markdown files and copy them to the clipboard, ready for being pasted right in the command line or anywhere else, or a tmux pane.
* [Runme](https://runme.dev/) - DevOps notebooks built with Markdown.
* [tldr](https://tldr.sh/) - Client for tldr pages, a community effort to simplify the beloved man pages with practical examples.
* [tlrc](https://tldr.sh/tlrc/) - Official tldr client written in Rust.

## <a name="ai-cli-commands"></a>AI terminal command generator

Generates or explains commands for the command line using AI.

* [wut](https://github.com/shobrook/wut) ⭐ 1,424 | 🐛 18 | 🌐 Python | 📅 2024-12-20 - An terminal assistant for the hopelessly confused; it explains the meaning of the output from the last command.
* [zev](https://github.com/dtnewman/zev) ⭐ 721 | 🐛 3 | 🌐 Python | 📅 2026-06-17 - A simple CLI tool to generate terminal commands using AI.
* [llm-term](https://github.com/dh1011/llm-term) ⭐ 154 | 🐛 1 | 🌐 C | 📅 2026-07-05 - A Rust-based CLI tool that generates and executes terminal commands using OpenAI's language models.
* [Octomind](https://github.com/muvon/octomind) ⭐ 114 | 🐛 1 | 🌐 Rust | 📅 2026-08-24 - Sessions-based AI coding agent with extensible architecture, smart codebase understanding and no AI provider lock-in.
* [Ollamacode CLI](https://github.com/tooyipjee/ollamacode) ⭐ 102 | 🐛 0 | 🌐 Python | 📅 2025-10-03 - The program creates a Python script from natural language and execute it automatically.
* [reTermAI](https://github.com/pie0902/reTermAI) ⭐ 55 | 🐛 0 | 🌐 Python | 📅 2025-07-06 - Smart command assistant for your terminal, using LLM.
* [cmd-ai](https://github.com/BrodaNoel/cmd-ai) ⭐ 51 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-04 - Natural language shell command generator and executor powered by AI.
* [LazyShell](https://github.com/bernoussama/lazyshell) ⭐ 44 | 🐛 12 | 🌐 TypeScript | 📅 2026-05-31 - AI CLI tool that generates and executes shell commands using AI.
* [osh](https://github.com/charyan/osh) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2024-01-19 - Ollama Shell Helper (osh): English to Unix-like Shell Commands translation using Local LLMs with Ollama.
* [c0admin](https://github.com/mbrell/c0admin) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2026-08-06 - A terminal-based AI assistant for Linux sysadmins. Uses the Gemini API.
* [ht](https://github.com/catallo/ht) ⭐ 39 | 🐛 0 | 🌐 Dart | 📅 2024-01-26 - A shell command that answers your questions about shell commands using OpenAI GPT.
* [Blitzdenk](https://github.com/Lommix/blitzdenk) ⭐ 9 | 🐛 0 | 🌐 Zig | 📅 2026-08-24 - A minimal multi provider coding agent and personal AI TUI; Similar to tools like opencode or claudecode; Written in Rust.
* [terminal-command](https://github.com/huss-mo/terminal-command) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-04-13 - A Python-based CLI tool for generating, and optionally executing, shell commands from natural language.
* [py-ai-shell](https://github.com/cheney-yan/py-ai-shell) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-04-27 - AI-powered shell for command line users.
* [OpenCode](https://opencode.ai/download) - AI coding agent, built for the terminal.
* [Spren](https://smadgulkar.github.io/spren/) - AI-powered terminal assistant that converts natural language to shell commands. Supports PowerShell, Bash, and CMD with intelligent command suggestions and safety checks.

# <a name="Media-and-Creative"></a>Media and Creative

## <a name="graphics"></a>Graphics

Applications to process images, colors, and ASCII art.

* [D2](https://github.com/terrastruct/d2) ⭐ 25,059 | 🐛 552 | 🌐 Go | 📅 2026-08-25 - D2 is a modern diagram scripting language that turns text to diagrams.
* [SVGO](https://github.com/svg/svgo) ⭐ 22,651 | 🐛 257 | 🌐 JavaScript | 📅 2026-08-24 - SVG Optimizer is a Node.js-based tool for optimizing SVG vector graphics files.
* [MapSCII](https://github.com/rastapasta/mapscii) ⭐ 9,222 | 🐛 52 | 🌐 JavaScript | 📅 2024-11-03 - A Braille & ASCII world map renderer for your console
* [pastel](https://github.com/sharkdp/pastel) ⭐ 6,463 | 🐛 38 | 🌐 Rust | 📅 2026-05-01 - A command-line tool to generate, analyze, convert and manipulate colors.
* [chafa](https://github.com/hpjansson/chafa) ⭐ 5,169 | 🐛 57 | 🌐 C | 📅 2026-08-21 - Terminal graphics for the 21 st century.
* [gifsicle](https://github.com/kohler/gifsicle) ⭐ 4,307 | 🐛 28 | 🌐 C | 📅 2026-01-31 - Create, manipulate, and optimize GIF images and animations.
* [GiF for CLI](https://github.com/google/gif-for-cli) ⚠️ Archived - Convert a GIF, short video or a query into ASCII art.
* [gowall](https://github.com/Achno/gowall) ⭐ 2,301 | 🐛 12 | 🌐 Go | 📅 2026-06-10 - A tool to convert a Wallpaper's color scheme / palette, image to pixel art, color palette extraction, image upsacling with Adversarial Networks  and more image processing features.
* [Diagon](https://github.com/ArthurSonzogni/Diagon) ⭐ 2,223 | 🐛 21 | 🌐 C++ | 📅 2025-05-16 - Diagon is an interactive interpreter, that transforms Markdown-style expression into an ASCII-art representation.
* [astroterm](https://github.com/da-luce/astroterm) ⭐ 2,018 | 🐛 38 | 🌐 C | 📅 2026-08-20 - A planetarium for your terminal. Explore stars, planets, constellations, and more!
* [durdraw](https://github.com/cmang/durdraw) ⭐ 1,793 | 🐛 4 | 🌐 Python | 📅 2026-08-18 - Versatile ASCII and ANSI Art text editor for drawing in the Linux/Unix/macOS terminal, with animation, 256 and 16 colors, Unicode and CP437, and customizable themes.
* [colout](https://github.com/nojhan/colout) ⭐ 1,163 | 🐛 14 | 🌐 Python | 📅 2026-06-14 - colout read lines of text stream on the standard input and output characters matching a given regular expression pattern in given color and style.
* [textual-paint](https://github.com/1j01/textual-paint) ⭐ 1,121 | 🐛 10 | 🌐 Python | 📅 2026-02-21 - MS Paint in your terminal (TUI).
* [imgp](https://github.com/jarun/imgp) ⭐ 1,091 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - A command line image resizer and rotator for JPEG and PNG images. It can resize (or thumbnail) and rotate thousands of images in a go, at lightning speed, while saving significantly on storage.
* [rclip](https://github.com/yurijmikhalevich/rclip) ⭐ 992 | 🐛 18 | 🌐 Python | 📅 2026-08-24 - AI-Powered Command-Line Photo Search Tool.
* [deviceframe](https://github.com/c0bra/deviceframe) ⭐ 595 | 🐛 16 | 🌐 JavaScript | 📅 2020-11-09 - Put device frames around mobile/web/progressive app screenshots.
* [figma-use](https://github.com/dannote/figma-use) ⭐ 591 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-03 - Control Figma from the command line with full read/write access for AI agents.
* [gifgen](https://github.com/lukechilds/gifgen) ⭐ 566 | 🐛 2 | 🌐 Shell | 📅 2023-01-22 - Simple high quality GIF encoding.
* [cmdpxl](https://github.com/knosmos/cmdpxl) ⭐ 549 | 🐛 2 | 🌐 Python | 📅 2021-08-27 - Command-line image editor (edit pixels, save images, undo function, fill tool and filters).
* [imgcat](https://github.com/trashhalo/imgcat) ⭐ 506 | 🐛 4 | 🌐 Go | 📅 2022-05-26 - Tool to output images in the terminal. Built with bubbletea.
* [haylxon](https://github.com/pwnwriter/haylxon) ⭐ 441 | 🐛 6 | 🌐 Rust | 📅 2026-07-28 - Blazing-fast tool to grab screenshots of your domain list right from terminal.
* [asciiMOL](https://github.com/dewberryants/asciiMol) ⭐ 418 | 🐛 0 | 🌐 Python | 📅 2026-06-24 - Curses based ASCII molecule viewer for terminals.
* [rimage](https://github.com/SalOne22/rimage) ⭐ 415 | 🐛 2 | 🌐 Rust | 📅 2026-08-21 - A powerful Rust image optimization CLI tool.
* [Korkut](https://github.com/oguzhaninan/korkut) ⭐ 385 | 🐛 6 | 🌐 TypeScript | 📅 2022-12-03 - Quick and simple image processing with the following functions: optimize, convert, crop, resize, rotate, watermark, flip.
* [Artem](https://github.com/FineFindus/artem) ⭐ 343 | 🐛 1 | 🌐 HTML | 📅 2025-06-15 - Convert images from multiple formats (JPG, PNG, WEBP, etc.) to ASCII art, written in Rust.
* [scrot](https://github.com/dreamer/scrot) ⭐ 238 | 🐛 8 | 🌐 C | 📅 2021-03-28 - SCReenshot - simple screenshot tool. Main features: window and retangular area capturing export to PNG JPG GIF and others.
* [objcurses](https://github.com/admtrv/objcurses) ⭐ 231 | 🐛 3 | 🌐 C++ | 📅 2025-05-24 - ncurses 3d object viewer.
* [givegif](https://github.com/passy/givegif) ⭐ 227 | 🐛 1 | 🌐 Haskell | 📅 2019-11-04 - GIFs on the command line.
* [ArTTY](https://github.com/mjwhitta/artty) ⭐ 132 | 🐛 0 | 🌐 Go | 📅 2026-06-25 - Pixel art with optional system info, similar to Neofetch.
* [kakikun](https://github.com/file-acomplaint/kakikun) ⭐ 103 | 🐛 4 | 🌐 Rust | 📅 2024-10-05 - Kakikun is a tool to paint, draw and create ASCII art in your terminal using Unicode characters.
* [Mercator](https://github.com/mrusme/mercator) ⭐ 93 | 🐛 0 | 🌐 Go | 📅 2025-12-15 - OpenStreetMap but as terminal user interface (TUI) program.
* [TermImg](https://github.com/srlehn/termimg) ⭐ 89 | 🐛 1 | 🌐 Go | 📅 2026-02-06 - termimg tries to draw images into terminals. The rectangular drawing area is given in cell coordinates (not pixels). Origin is the upper-left corner.
* [img2ascii](https://github.com/JosefVesely/Image-to-ASCII) ⭐ 74 | 🐛 2 | 🌐 C | 📅 2026-05-05 - Convert images to ASCII art.
* [mandelbrot-cli](https://github.com/MicheleFiladelfia/mandelbrot-cli) ⭐ 49 | 🐛 1 | 🌐 Go | 📅 2024-11-13 - Multiplatform terminal mandelbrot set explorer.
* [greentext](https://github.com/jasonuc/greentext) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2026-08-24 - A CLI tool for creating green-text memes.
* [catnip](https://github.com/sweetbbak/catnip) ⭐ 27 | 🐛 1 | 🌐 Shell | 📅 2023-11-23 - An Image picker using pure bash (C and Go version in the works) and kittys icat and Chafa's Sixel protocol.
* [3D-renderer](https://github.com/rashid-360/3D-renderer) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2025-03-26 - A console-based 3D renderer that uses ASCII characters to display and rotate 3D shapes.
* [pik](https://github.com/immanelg/pik) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2024-08-28 - Color picker for terminal.
* [inklayers](https://github.com/toolleeo/inklayers) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2022-09-30 - A command line program that exports layers from an SVG file. It can be used to create slide shows by editing a single SVG file.
* [svgshift](https://github.com/10xJSChad/svgshift) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2025-10-26 - Command-line utility to quickly adjust the colors in an svg file. Allows for quick and easy color manipulation of svg files by adjusting RGB and HSL values.
* [ghost-image-cleaner](https://github.com/DeadSwitch404/ghost-image-cleaner) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2025-07-18 - If you share, do it like a Ghost... No metadata, no filename fingerprint, no trace.
* [LinuxSSTool](https://github.com/DatCodeMania/LinuxSSTool) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-06-21 - A simple script that takes a screenshot and adds a gradated border using ImageMagick.
* [Favicon Editor](https://github.com/xyproto/favicon-editor) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-08-14 - Minimalist grayscale favicon editor for the terminal.
* [TerrainGenerator](https://github.com/NM711/TerrainGenerator) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2025-10-18 - 2D Terrain Generator to create procedural 2D worlds and maps.
* [Aewan](http://aewan.sourceforge.net/) - Aewan is a multi-layered ASCII graphics/animation editor. It produces stand-alone cat-able ASCII art files and an easy-to-parse format for integration into terminal applications.
* [BlockPaint](https://github.com/wooster0/blockpaint) - BlockPaint is a painting program that allows you to draw pixel graphics in the terminal using the mouse.
* [GraphicsMagick](http://www.graphicsmagick.org/) - Swiss army knife of image processing.
* [Graphviz](https://graphviz.org/) - Graphviz is open source graph visualization software. It contains several command line tools to generate and manipulate graphs.
* [heroshot](https://heroshot.sh) - Screenshot automation CLI for documentation. Visual element picker to define captures and config-driven regeneration with one command.
* [ImageMagick](http://www.imagemagick.org/script/index.php) - Software suite to create, edit, compose, or convert bitmap images; it handles many file formats (including PDF and SVG) and provides processing tools to "resize, flip, mirror, rotate, distort, shear and transform images, adjust image colors, apply various special effects, or draw text, lines, polygons, ellipses and Bézier curves".
* [jp2a](https://csl.name/jp2a/) - Command-line tool that converts images to ASCII art in the Linux terminal.
* [LinuxLogo](https://sourceforge.net/projects/linuxlogo/) - Display the Linux distribution logo in ASCII format.
* [zbar](https://zbar.sourceforge.net/) - ZBar reads bar codes from various sources, such as video streams and image files. It supports many popular ypes of bar codes including QR Codes.

## <a name="video"></a>Video

Programs to process and manage video files (downloader, editing, players, etc.).

* [Streamlink](https://github.com/streamlink/streamlink) ⭐ 11,710 | 🐛 76 | 🌐 Python | 📅 2026-08-24 - Streamlink is a CLI utility which pipes video streams from various services into a video player.
* [Editly](https://github.com/mifi/editly) ⭐ 5,477 | 🐛 80 | 🌐 TypeScript | 📅 2025-05-12 - A tool and framework for declarative NLE (non-linear video editing) using Node.js and FFmpeg.
* [ffscreencast](https://github.com/cytopia/ffscreencast) ⭐ 1,824 | 🐛 20 | 🌐 Shell | 📅 2024-07-16 - A FFmpeg screencast with video overlay and multi monitor support.
* [yt-x](https://github.com/Benexl/yt-x) ⭐ 1,644 | 🐛 12 | 🌐 Shell | 📅 2026-08-19 - Browse youtube from your terminal, with text-based UI using `fzf` or `rofi` for seamless navigation.
* [ytsurf](https://github.com/Stan-breaks/ytsurf) ⭐ 592 | 🐛 1 | 🌐 Shell | 📅 2026-08-10 - Youtube in the terminal (syncplay support, audio-only playback and downloads, download videos, history).
* [invidtui](https://github.com/darkhz/invidtui) ⭐ 205 | 🐛 8 | 🌐 Go | 📅 2024-07-14 - Invidious TUI client, which fetches data from invidious instances and displays a user interface in the terminal, and allows for selecting and playing YouTube audio and video.
* [FFMPerative](https://github.com/remyxai/FFMPerative) ⭐ 203 | 🐛 4 | 🌐 Python | 📅 2026-06-07 - Powered by Large Language Models (LLMs) through an intuitive chat interface, now you can compose video edits in natural language.
* [Pyutube](https://github.com/Hetari/pyutube) ⭐ 81 | 🐛 1 | 🌐 Python | 📅 2026-05-18 - A simple tool to download YouTube video shorts and playlist in just one click.
* [lotc](https://github.com/ranelpadon/lord-of-the-clips) ⭐ 68 | 🐛 1 | 🌐 Python | 📅 2023-02-20 - (Lord Of The Clips) Video downloader, trimmer, and merger using the terminal. Supports YouTube, Facebook, Reddit, Twitter, etc. Downloads/trims at multiple points. Merges multiple clips.
* [videoinfox](https://github.com/powerhousepro69/videoinfox) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2023-03-26 - Find videos fast. Powerful playlist building and editing. A play queue to load up unlimited playlists. Index unlimited video libraries and find videos by keyword. Download list building without leaving the browser and a Download Queue.
* [CreateVideoMeme](https://github.com/hache0099/CreateMemeVideo) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2023-06-08 - Bash tool to add captions to the top of videos.
* [subauto](https://github.com/ricjuanflores/subauto) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2025-01-23 - CLI tool for transcribing, translating, and embedding subtitles in videos using Gemini AI.
* [ffmpeg](https://ffmpeg.org/) - The Swiss knife of video editing from the command line.
* [VLC](https://code.videolan.org/videolan/vlc) - VLC media player and multimedia engine; Can play most multimedia files: files, discs, streams, devices; It's also able to convert, encode, stream and manipulate streams into numerous formats.
* [YouTube TUI](https://siriusmart.github.io/youtube-tui/) - A lightweight and user-friendly TUI for browsing YouTube content from the terminal.

## <a name="music"></a>Sound and music

Podcast, synthesizers, downloaders, online radios.

* [Spotify TUI](https://github.com/Rigellute/spotify-tui) ⭐ 19,315 | 🐛 306 | 🌐 Rust | 📅 2024-04-04 - A Spotify client for the terminal written in Rust.
* [beets](https://github.com/beetbox/beets) ⭐ 15,578 | 🐛 711 | 🌐 Python | 📅 2026-08-24 - Beets is the media library management system for obsessive music geeks: catalogs your collection, automatically improving its metadata as it goes.
* [mps-youtube](https://github.com/mps-youtube/yewtube) ⭐ 8,782 | 🐛 226 | 🌐 Python | 📅 2026-03-04 - A curses player for music tracks from YouTube; it allows searching for songs and playlists; it downloads the video, extracts the audio track and plays it; handles local playlists and many configuration parameters.
* [spotify-player](https://github.com/aome510/spotify-player) ⭐ 7,117 | 🐛 165 | 🌐 Rust | 📅 2026-07-20 - spotify-player is a fast, easy to use, and configurable terminal music player having feature parity with the official Spotify application.
* [ncspot](https://github.com/hrkfdn/ncspot) ⭐ 6,737 | 🐛 210 | 🌐 Rust | 📅 2026-08-21 - Cross-platform ncurses Spotify client written in Rust, inspired by ncmpc and the likes.
* [Tizonia](https://github.com/tizonia/tizonia-openmax-il) ⭐ 1,733 | 🐛 172 | 🌐 C | 📅 2026-08-16 - Command-line cloud music player for Linux with support for Spotify, Google Play Music, YouTube, SoundCloud, TuneIn, iHeartRadio, Plex servers and Chromecast devices.
* [Instant Music Downloader](https://github.com/yask123/Instant-Music-Downloader) ⭐ 1,445 | 🐛 48 | 🌐 Roff | 📅 2021-01-27 - Instantly download any song!
* [soundcloud2000](https://github.com/grobie/soundcloud2000) ⚠️ Archived - A terminal client for soundcloud.
* [PyRadio](https://github.com/coderholic/pyradio) ⭐ 1,091 | 🐛 11 | 🌐 Python | 📅 2026-05-07 - Curses based internet radio player.
* [pulsemixer](https://github.com/GeorgeFilipkin/pulsemixer) ⭐ 808 | 🐛 36 | 🌐 Python | 📅 2024-03-14 - CLI and curses mixer for PulseAudio.
* [upiano](https://github.com/eliasdorneles/upiano) ⭐ 792 | 🐛 5 | 🌐 Python | 📅 2025-07-09 - A Piano in your terminal (TUI).
* [ytui-music](https://github.com/sudipghimire533/ytui-music) ⭐ 773 | 🐛 37 | 🌐 Rust | 📅 2025-03-03 - YouTube client in terminal for music (lightweight YouTube client).
* [castero](https://github.com/xgi/castero) ⭐ 683 | 🐛 32 | 🌐 Python | 📅 2026-04-21 - A TUI podcast client for the terminal.
* [radio-active](https://github.com/deep5050/radio-active) ⭐ 593 | 🐛 16 | 🌐 Python | 📅 2026-06-30 - Internet radio player with 40k+ stations.
* [jellyfin-tui](https://github.com/dhonus/jellyfin-tui) ⭐ 577 | 🐛 24 | 🌐 Rust | 📅 2026-08-09 - Jellyfin client (music streaming); Offers a self-hosted terminal music player with modern features.
* [spotui](https://github.com/ceuk/spotui) ⭐ 575 | 🐛 8 | 🌐 Python | 📅 2023-07-25 - TUI Spotify client written in Python.
* [opencubicplayer](https://github.com/mywave82/opencubicplayer) ⭐ 437 | 🐛 16 | 🌐 C | 📅 2026-08-24 - Open Cubic Player (UNIX fork) is a music visualizer for various tracked music formats (amiga modules, S3M, IT), chiptunes and other formats related to demoscene.
* [kord](https://github.com/synestematic/kord) ⭐ 385 | 🐛 2 | 🌐 Python | 📅 2025-03-18 - A Python framework that provides programmers with a simple API for the creation of music-based applications.
* [asak](https://github.com/chaosprint/asak) ⭐ 371 | 🐛 11 | 🌐 Rust | 📅 2026-04-11 - A cross-platform audio recording/playback TUI written in Rust.
* [dzr](https://github.com/yne/dzr) ⭐ 263 | 🐛 3 | 🌐 Shell | 📅 2026-03-15 - Command Line deezer.com Player for Linux, BSD, Android, Windows.
* [mufetch](https://github.com/ashish0kumar/mufetch) ⭐ 206 | 🐛 0 | 🌐 Go | 📅 2026-02-20 - CLI for music display (album covers and artist information) with comprehensive metadata, clickable links, responsive sizing and cross-platform support.
* [Toutui](https://github.com/AlbanDAVID/Toutui) ⚠️ Archived - A TUI Audiobookshelf Client for Linux and macOS (supports audiobooks and podcasts, play directly without downloading).
* [Tera](https://github.com/shinokada/tera) ⭐ 166 | 🐛 17 | 🌐 Go | 📅 2026-04-09 - Terminal Radio: an easy-to-use CLI music player to play favorite music, radio stations and explore various radio stations from the terminal only.
* [RadioGoGo](https://github.com/Zi0P4tch0/RadioGoGo) ⭐ 165 | 🐛 3 | 🌐 Go | 📅 2026-06-12 - Go-powered CLI to surf global radio waves with TUI.
* [mpvc](https://github.com/gmt4/mpvc) ⭐ 157 | 🐛 1 | 🌐 Shell | 📅 2026-08-23 - A minimal mpc-like CLI and TUI for controlling mpv from the shell.
* [line](https://github.com/pd3v/line) ⭐ 152 | 🐛 0 | 🌐 C++ | 📅 2025-08-11 - Tiny command-line midi sequencer and language for live coding.
* [yt-audio](https://github.com/RijulGulati/yt-audio) ⭐ 134 | 🐛 1 | 🌐 Python | 📅 2020-08-03 - A simple, configurable youtube-dl wrapper to download and manage YouTube audio.
* [muCLIar](https://github.com/aayush1205/muCLIar) ⭐ 125 | 🐛 1 | 🌐 Python | 📅 2020-10-03 - YouTube automator bringing you your music right on your CLI.
* [discodos](https://github.com/JOJ0/discodos) ⭐ 84 | 🐛 4 | 🌐 Python | 📅 2025-08-27 - A CLI tool for DJ's and record collectors based on the discogs.com collection feature that allows analyzing and organize DJ sets.
* [sonicradio](https://github.com/dancnb/sonicradio) ⭐ 84 | 🐛 5 | 🌐 Go | 📅 2026-01-23 - A TUI radio player making use of Radio Browser API and Bubbletea.
* [cli-viz](https://github.com/sam1am/cli-viz) ⭐ 77 | 🐛 0 | 🌐 Python | 📅 2026-05-27 - An audio visualizer that runs in the linux terminal and reacts to the microphone.
* [BadaBoomBooks](https://github.com/WirlyWirly/BadaBoomBooks) ⭐ 68 | 🐛 7 | 🌐 Python | 📅 2024-05-22 - Quickly organize audiobooks using a terminal and web-browser.
* [mzk](https://github.com/acidvegas/mzk) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2024-01-21 - Music theory helper.
* [Aurras](https://github.com/vedant-asati03/Aurras) ⚠️ Archived - Enhances your music experience with an intuitive TUI and seamless Spotify integration, easily navigate your music library, access playlists, and get recommendations based on your listening habits.
* [gadacz](https://github.com/rareitems/gadacz) ⭐ 42 | 🐛 5 | 🌐 Rust | 📅 2024-06-27 - Audiobook player (and other audio files) TUI.
* [sptui](https://github.com/szktkfm/sptui) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2026-05-17 - Spotify TUI player, written in Go.
* [Detify](https://github.com/omenmn/detify) ⭐ 32 | 🐛 0 | 🌐 Shell | 📅 2025-07-06 - CLI tool that automatically downloads your currently playing Spotify track using spotdl, with both manual and auto-download modes.
* [cTune](https://github.com/An7ar35/ctune) ⭐ 31 | 🐛 3 | 🌐 C | 📅 2026-04-18 - A ncurses based internet radio player written in C for Linux.
* [podbit](https://github.com/ejv2/podbit) ⭐ 28 | 🐛 3 | 🌐 Go | 📅 2026-02-04 - Podbit is a replacement for newsboat's standard podboat tool for listening to podcasts. It is minimal, performant and tries to focus just on being a podcast client, rather than an RSS reader.
* [pytunes](https://github.com/bernhardfritz/pytunes) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2023-11-21 - Self-hosted music streaming service.
* [spytorec](https://github.com/Danidukiyu/SpytoRec) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-06-28 - Real-time Spotify recorder with automatic track splitting, metadata tagging, and high-quality FLAC/OGG output.
* [fme](https://github.com/andreykaere/fme) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2023-12-09 - Flexible metadata editor that allows editing the metadata of music files.
* [Podcli](https://github.com/Air08/Podcli) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-10-26 - Terminal Based Podcast Client with search, subscription management, and playback features.
* [music](https://github.com/kitesi/music) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2026-07-05 - Command line tool to help with music related tasks, such as querying songs, lastfm scrobbling, lastfm suggestions, spotify - local playlist sync.
* [radio-beats](https://github.com/quangnguyen30192/radio-beats) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2023-11-01 - Rofi-like menu for playing radio stations.
* [bash\_radio\_player](https://github.com/gokayburuc/bash_radio_player) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-03-27 - Terminal Radio Player using mpv and fzf.
* [Alsamixer](http://www.alsa-project.org/main/index.php/Main_Page) - ALSA mixer with curses interfaces.
* [espeak](http://espeak.sourceforge.net/) - A compact open source software speech synthesizer for English and other languages.
* [lltag](http://bgoglin.free.fr/lltag/) - Bulk edit MP3 tags.
* [musicScraper](https://github.com/mBaratta96/musicScraper) - CLI tool for scraping information from musical websites (Rateyourmusic, Metal Archives), with nice album ASCII art.
* [nap](https://nap.sourceforge.net/) - Linux napster client.
* [podboat](https://newsboat.org/) - A podcast download manager for text terminals, a companion for the newsboat RSS-reader.
* [Siren](https://www.kariliq.nl/siren/) - Siren is a text-based audio player for UNIX-like operating systems.

## <a name="audio-player"></a>Music players

Players for local sound files and music.

* [musikcube](https://github.com/clangen/musikcube) ⭐ 4,829 | 🐛 178 | 🌐 C++ | 📅 2026-03-23 - A cross-platform, terminal-based audio engine, library, player and server written in C++.
* [cue](https://github.com/ravachol/cue) ⭐ 2,990 | 🐛 3 | 🌐 C | 📅 2026-08-24 - A command-line music player.
* [kew](https://github.com/ravachol/kew) ⭐ 2,990 | 🐛 3 | 🌐 C | 📅 2026-08-24 - A command-line music player with gapless playback and simple playlist management.
* [termusic](https://github.com/tramhao/termusic) ⭐ 2,180 | 🐛 49 | 🌐 Rust | 📅 2026-08-24 - Terminal Music Player written in Rust.
* [maestro-cli](https://github.com/PrajwalVandana/maestro-cli) ⭐ 231 | 🐛 0 | 🌐 Python | 📅 2026-05-10 - A command-line tool to play songs (or any audio, really) in the terminal.
* [Gomu](https://github.com/issadarkthing/gomu) ⭐ 211 | 🐛 11 | 🌐 Go | 📅 2026-06-05 - Gomu is intuitive, powerful CLI music player. It has embedded scripting language and event hook to enable user to customize their config extensively.
* [jammer](https://github.com/jooapa/jammer) ⭐ 158 | 🐛 0 | 🌐 C# | 📅 2026-08-20 - Multiplatform light-weight TUI music player with Soundcloud & Youtube support, with effects.
* [MusicPlayerPlus](https://github.com/doctorfree/MusicPlayerPlus) ⭐ 101 | 🐛 0 | 🌐 Shell | 📅 2024-07-15 - Featureful ncurses based MPD client inspired by ncmpc with integration for Beets, spectrum visualization,Bandcamp/Soundcloud, asciimatics, cantata, and more.
* [mfp](https://github.com/guptarohit/mfp) ⭐ 63 | 🐛 2 | 🌐 Rust | 📅 2026-05-28 - A command-line utility for playing music mixes for programming & focus (from [musicforprogramming.net](musicforprogramming.net)), unlocking the flow state.
* [lowfi](https://github.com/remvze/lowfi) ⭐ 50 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-05 - A music player through your terminal, with the option to open YouTube in the browser.
* [kmp3](https://github.com/korei999/kmp3) ⭐ 40 | 🐛 0 | 🌐 C++ | 📅 2025-12-19 - Little music player with some peculiar characteristics.
* [Mplay](https://github.com/unpythonic-coder/mplay) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-07-28 - Full featured music player for the command line, inspired by cplay.
* [amused](https://projects.omarpolo.com/amused.html) - Minimal music player that composes well, or aims to do so, with other tools thought.
* [cmus](https://cmus.github.io/) - A fast and lightweight audio player with configurable keybindings and playlist support.
* [MOC](https://moc.daper.net/) - (music on console) - a powerful and easy to use console audio player, user interface a la Midnight Commander, plenty of features, fully controllable from the keyboard.
* [Mp3blaster](http://www.mp3blaster.org/?m=1) - Audio player for the text console.
* [mpg123](http://mpg123.org/) - Quick `mp3` sound file player; no visual interface, just a command-line audio file player for `mp3` files.
* [ncmpcpp](https://rybczak.net/ncmpcpp/) - NCurses Music Player Client (Plus Plus) - featureful ncurses based MPD client inspired by ncmpc. Relevant features: tag editor, playlist editor, easy to use search engine, media library, music visualizer, ability to fetch artist info from [last.fm](https://www.last.fm/), new display mode, alternative user interface, ability to browse and add files from outside of MPD music directory.
* [ogg123](https://www.xiph.org/downloads/) - Quick `ogg` sound file player; no visual interface, just a command-line audio file player for the free and open `ogg` file format.
* [rmpc](https://mierak.github.io/rmpc/) - A configurable TUI MPD client inspired by ncmpcpp and ranger with album art support via various graphics protocols.

## <a name="animation"></a>Animation

Generate or display animated graphics and effects.

* [ora](https://github.com/sindresorhus/ora) ⭐ 9,740 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-22 - Elegant terminal spinner.
* [No More Secrets](https://github.com/bartobri/no-more-secrets) ⭐ 7,802 | 🐛 1 | 🌐 C | 📅 2025-12-13 - A command line tool that recreates the famous data decryption effect seen in the 1992 movie Sneakers.
* [terminaltexteffects](https://github.com/ChrisBuilds/terminaltexteffects) ⭐ 4,177 | 🐛 7 | 🌐 Python | 📅 2026-06-10 - TerminalTextEffects (TTE) is a terminal visual effects engine, application, and Python library.
* [sha256-animation](https://github.com/in3rsha/sha256-animation) ⭐ 3,398 | 🐛 3 | 🌐 Ruby | 📅 2024-03-06 - Animation of the SHA-256 hash function in your terminal.
* [nyancat](https://github.com/klange/nyancat) ⭐ 1,584 | 🐛 17 | 🌐 C | 📅 2024-04-19 - Nyancat in your terminal, rendered through ANSI escape sequences.
* [ternimal](https://github.com/p-e-w/ternimal) ⭐ 1,112 | 🐛 14 | 🌐 Rust | 📅 2018-11-19 - Simulate a life form in the terminal.
* [neo](https://github.com/st3w/neo) ⭐ 951 | 🐛 16 | 🌐 C++ | 📅 2024-04-02 - Recreates the digital rain effect from "The Matrix". Streams of random characters will endlessly scroll down your terminal screen.
* [ascii-movie](https://github.com/gabe565/ascii-movie) ⭐ 614 | 🐛 43 | 🌐 Go | 📅 2026-08-24 - Allows to play the ASCII art Star War movie locally or it can open a connection to play it over SSH or telnet.
* [firew0rks](https://github.com/addyosmani/firew0rks) ⭐ 574 | 🐛 2 | 🌐 JavaScript | 📅 2024-12-31 - Fireworks in your terminal.
* [rusty-rain](https://github.com/cowboy8625/rusty-rain) ⭐ 474 | 🐛 4 | 🌐 Rust | 📅 2026-08-19 - A cross platform matrix rain made with Rust.
* [paclear](https://github.com/orangekame3/paclear) ⭐ 237 | 🐛 2 | 🌐 Go | 📅 2024-05-17 - paclear is a clear command with pacman animation.
* [go-life](https://github.com/sachaos/go-life) ⭐ 147 | 🐛 5 | 🌐 Go | 📅 2024-12-29 - Terminal based Conway's Game of Life, implemented in Go.
* [PyBonsai](https://github.com/Ben-Edwards44/PyBonsai) ⭐ 145 | 🐛 2 | 🌐 Python | 📅 2026-04-16 - Generate procedural ASCII art trees in the terminal.
* [aclock](https://github.com/tenox7/aclock) ⭐ 105 | 🐛 4 | 🌐 C | 📅 2026-05-25 - Ascii analog clock for text console displays and terminals and terminal emulators.
* [cli-mandelbrot](https://github.com/danyshaanan/cli-mandelbrot) ⭐ 105 | 🐛 1 | 🌐 JavaScript | 📅 2019-03-18 - A CLI for traversing the Mandelbrot fractal.
* [gostty](https://github.com/ashish0kumar/gostty) ⭐ 95 | 🐛 1 | 🌐 Go | 📅 2025-07-09 - Animation of a ghost for the terminal.
* [Maze TUI](https://github.com/agl-alexglopez/maze-tui) ⭐ 84 | 🐛 0 | 🌐 Rust | 📅 2025-10-24 - Build mazes, solve them with various algorithms and visualize them.
* [cpond](https://github.com/ayuzur/cpond) ⭐ 82 | 🐛 3 | 🌐 C | 📅 2025-11-23 - The program creates procedurally animated fish to swim around your terminal.
* [cli-fireplace](https://github.com/dolsup/cli-fireplace) ⭐ 68 | 🐛 0 | 🌐 JavaScript | 📅 2018-12-25 - Shows digital fireplace.
* [Go-L](https://github.com/Jeadie/Go-L) ⭐ 60 | 🐛 0 | 🌐 Go | 📅 2022-11-07 - Game of Life with different update rules and on a bunch of different topologies (sphere, torus, klein bottle, etc.).
* [ctree](https://github.com/gleich/ctree) ⭐ 48 | 🐛 0 | 🌐 Go | 📅 2026-01-01 - A Christmas tree right from your terminal.
* [LundukeHoliday](https://github.com/BryanLunduke/LundukeHoliday) ⭐ 38 | 🐛 1 | 🌐 Shell | 📅 2022-12-27 - A simple Bash script that shows some animated, ASCII holiday decorations in your shell.
* [bb](https://github.com/stroucki/bb) ⭐ 37 | 🐛 0 | 🌐 C | 📅 2026-03-11 - The portable BB demo of AAlib, with fixes for vax etc.
* [gof-rs](https://github.com/omagdy7/gof-rs) ⭐ 27 | 🐛 0 | 🌐 Rust | 📅 2025-08-05 - Game of life rendered in your terminal with over 500+ unique patterns to choose from.
* [cellscape](https://github.com/ashish0kumar/cellscape) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2025-07-09 - TUI simulator for eight classic cellular automata.
* [ccube](https://github.com/hamza512b/ccube) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2025-06-21 - Rotating 3d cube in terminal; written in C.
* [console-fun](https://github.com/akgondber/console-fun) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-14 - Some console stuff to have a fun and watch some animations with texts, figures, etc.
* [Maze Solver](https://github.com/Vlamonster/maze_solver_rust) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2023-01-12 - Generate, display and solve mazes in an animated way in the terminal.
* [rich\_life](https://github.com/paulrobello/rich_life) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-10-25 - Conway's Game of Life and Langton's Ant.
* [terminal-art](https://github.com/Eric-Lennartson/terminal-art) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2023-11-19 - Art made in the terminal: rotating cube.
* [Binary Clock](https://github.com/tom-on-the-internet/binary-clock) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2024-04-08 - Displays a clock where numbers are represented with blue and gray dots with binary encoding.
* [cgol](https://github.com/lporanta/cgol) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-04-18 - Conway's Game of Life in C.
* [gol-tui](https://github.com/MathiasSven/gol-tui) ⭐ 2 | 🐛 0 | 🌐 Haskell | 📅 2023-12-30 - Conway's Game of Life TUI.
* [The Cognitive Sandbox](https://github.com/sylcrala/cognitive_sandbox) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-01-04 - The project is a local simulation environment that allows individual agents (particles) to interact with and remeber each other across sessions.
* [animatrix](https://gitlab.com/christosangel/animatrix) - C program that will create some basic animation of ascii-art loaded from a txt file, while rendering the matrix effect in the terminal window.
* [ascii-matrix](https://gitlab.com/christosangel/ascii-matrix) - This script written in the C language, will render the matrix effect in the terminal, while rendering ASCII art loaded from a txt file, at the center of the terminal window.
* [asciicquarium](http://www.robobunny.com/projects/asciiquarium/html/) - Enjoy the mysteries of the sea from the safety of your own terminal!
* [c-pipes](https://gitlab.com/christosangel/c-pipes) - Program written in the C language that will render random coloured zigzag lines in the terminal, while the font, speed, density and number of lines are fully costumizable. Each line stops once it reaches the edge of the window, only for a new line to begin.
* [c-squares](https://gitlab.com/christosangel/c-squares) - Program written in C that will render random coloured rectangulars in the terminal, while the font, speed, density, color, ratio and number of the shapes drawn are fully costumizable.
* [cbonsai](https://gitlab.com/jallbrit/cbonsai) - A bonsai tree generator, written in C using ncurses. It intelligently creates, colors, and positions a bonsai tree.
* [chaftrix](https://gitlab.com/christosangel/chaftrix) - C program that will render the matrix effect in the terminal window in the background, while rendering an image in the foreground, allowing animation of this image in one or two dimensions.
* [cmatrix](http://www.asty.org/cmatrix/) - ncurses program that display the scrolling lines found in the movie `The matrix`.
* StarWars vision - See Star Wars in ASCII with `telnet towel.blinkenlights.nl` (server seems down recently - I leave the link in the hope that it will be resumed in the future).
* [Steam Locomotive](http://www.cyberciti.biz/tips/displays-animations-when-accidentally-you-type-sl-instead-of-ls.html) - A steam locomotive traverses the screen from right to left if `sl` is typed instead of `ls`.

## <a name="viewers"></a>Viewers

File viewers for images and other formats (e.g., e-books).

* [bat](https://github.com/sharkdp/bat) ⭐ 60,246 | 🐛 424 | 🌐 Rust | 📅 2026-08-11 - A cat clone with syntax highlighting and Git integration.
* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,262 | 🐛 34 | 🌐 Rust | 📅 2026-04-30 - Command-line hex viewer.
* [CAVA](https://github.com/karlstav/cava) ⭐ 6,368 | 🐛 17 | 🌐 C | 📅 2026-08-18 - Cross-platform Audio Visualizer.
* [haxor-news](https://github.com/donnemartin/haxor-news) ⭐ 4,088 | 🐛 42 | 🌐 Python | 📅 2022-04-22 - Browse Hacker News like a haxor: A Hacker News command line interface (CLI).
* [ccat](https://github.com/owenthereal/ccat) ⭐ 3,207 | 🐛 41 | 🌐 Go | 📅 2022-09-05 - `cat` with colorized output.
* [timg](https://github.com/hzeller/timg) ⭐ 2,730 | 🐛 36 | 🌐 C++ | 📅 2026-08-05 - A terminal image and video viewer.
* [ov](https://github.com/noborus/ov) ⭐ 2,008 | 🐛 30 | 🌐 Go | 📅 2026-08-23 - Feature-rich terminal-based text viewer.
* [TerminalImageViewer](https://github.com/stefanhaustein/TerminalImageViewer) ⭐ 1,683 | 🐛 17 | 🌐 C++ | 📅 2026-08-03 - Small C++ program to display images in a (modern) terminal using RGB ANSI codes and Unicode block graphics characters.
* [nerdlog](https://github.com/dimonomid/nerdlog) ⭐ 1,548 | 🐛 15 | 🌐 Go | 📅 2025-06-22 - Fast, remote-first, multi-host TUI log viewer with timeline histogram and no central server.
* [mcat](https://github.com/Skardyy/mcat) ⭐ 1,386 | 🐛 12 | 🌐 Rust | 📅 2026-08-22 - Terminal image, video, directory, and Markdown viewer.
* [youtube-viewer](https://github.com/trizen/youtube-viewer) ⭐ 1,311 | 🐛 45 | 🌐 Perl | 📅 2026-06-15 - Lightweight application that searches and streams videos from YouTube.
* [epy](https://github.com/wustho/epy) ⭐ 1,213 | 🐛 72 | 🌐 Python | 📅 2024-03-17 - CLI Ebook (epub2, epub3, fb2, mobi) Reader.
* [medium-cli](https://github.com/djadmin/medium-cli) ⭐ 734 | 🐛 42 | 🌐 JavaScript | 📅 2026-02-13 - Medium for Hackers - Read [medium.com](https://medium.com/) stories in the terminal.
* [hackernews-TUI](https://github.com/aome510/hackernews-TUI) ⭐ 719 | 🐛 9 | 🌐 Rust | 📅 2026-03-29 - A Terminal UI to browse Hacker News.
* [fancy-cat](https://github.com/freref/fancy-cat) ⭐ 556 | 🐛 20 | 🌐 Zig | 📅 2026-08-03 - CLI PDF reader with Vim keybindings.
* [baca](https://github.com/wustho/baca) ⭐ 519 | 🐛 12 | 🌐 Python | 📅 2024-03-05 - Lets you indulge in your favorite e-books in the comfort of your terminal.
* [viu](https://github.com/learn-anything/command-line-tools) ⭐ 494 | 🐛 16 | 📅 2026-08-16 - Command-line application to view images from the terminal written in Rust.
* [GopherTube](https://github.com/krishnassh/gophertube) ⭐ 425 | 🐛 2 | 🌐 Go | 📅 2026-08-19 - A terminal-based YouTube client that scrapes YouTube search results and uses mpv for video playback.
* [reader](https://github.com/mrusme/reader) ⭐ 411 | 🐛 0 | 🌐 Go | 📅 2026-07-21 - Reader parses a web page for its actual content and displays it in nicely highlighted text on the command line
* [hygg](https://github.com/kruserr/hygg) ⭐ 350 | 🐛 15 | 🌐 Rust | 📅 2026-07-17 - Minimalistic Vim-like TUI document reader.
* [Yozefu](https://github.com/MAIF/yozefu) ⭐ 344 | 🐛 16 | 🌐 Rust | 📅 2026-08-18 - An TUI for exploring data of a Kafka cluster.
* [hnterm](https://github.com/ggerganov/hnterm) ⭐ 319 | 🐛 5 | 🌐 C++ | 📅 2024-08-07 - Hacker News in the terminal.
* [termv](https://github.com/Roshan-R/termv) ⭐ 299 | 🐛 7 | 🌐 Shell | 📅 2026-05-27 - A terminal IPTV player written in bash.
* [see](https://github.com/guilhermeprokisch/see) ⭐ 285 | 🐛 5 | 🌐 Rust | 📅 2026-07-22 - A cute cat for the terminal with advanced code viewing, Markdown rendering, tree-sitter syntax highlighting, images view and more.
* [dashbrew](https://github.com/rasjonell/dashbrew) ⭐ 269 | 🐛 1 | 🌐 Go | 📅 2026-05-15 - TUI dashboard builder that lets you visualize data from scripts and APIs.
* [vv](https://github.com/wolfpld/vv) ⚠️ Archived - A terminal image viewer, supporting an extensive range of modern image formats.
* [ucollage](https://github.com/ckardaris/ucollage) ⚠️ Archived - An extensible command line image viewer inspired by vim.
* [nbpreview](https://github.com/paw-lu/nbpreview) ⭐ 206 | 🐛 37 | 🌐 Python | 📅 2025-10-21 - A terminal viewer for Jupyter notebooks. It's like cat for ipynb files.
* [moulti](https://github.com/xavierog/moulti) ⭐ 166 | 🐛 2 | 🌐 Python | 📅 2026-02-05 - Moulti is a CLI-driven Terminal User Interface (TUI) displaying arbitrary outputs inside visual, collapsible blocks called steps.
* [bbcli](https://github.com/hako/bbcli) ⭐ 142 | 🐛 0 | 🌐 Rust | 📅 2026-07-02 - Browse BBC News like a hacker.
* [texel](https://github.com/Lauriat/texel) ⭐ 133 | 🐛 0 | 🌐 Python | 📅 2022-02-14 - Command line interface for reading spreadsheets inside terminal.
* [Lob TUI](https://github.com/pythops/lobtui) ⭐ 121 | 🐛 3 | 🌐 Rust | 📅 2025-05-16 - TUI for lobste.rs website.
* [brows](https://github.com/rubysolo/brows) ⭐ 83 | 🐛 0 | 🌐 Go | 📅 2026-06-01 - CLI GitHub release browser.
* [krafna](https://github.com/7sedam7/krafna) ⭐ 78 | 🐛 6 | 🌐 Rust | 📅 2026-03-31 - Obsidion dataview plugin-like tool for command line.
* [rfc\_reader](https://github.com/ozan2003/rfc_reader) ⭐ 73 | 🐛 0 | 🌐 Rust | 📅 2026-08-15 - A tool to read RFCs (Request for Comments) with a TUI, allowing you to fetch, cache, and browse RFC documents.
* [btail](https://github.com/galalen/btail) ⭐ 57 | 🐛 6 | 🌐 Go | 📅 2026-03-02 - Interactive file tail viewer.
* [kplay](https://github.com/dhth/kplay) ⭐ 52 | 🐛 1 | 🌐 Go | 📅 2026-06-09 - Inspect messages in a Kafka topic in a simple and deliberate manner.
* [nbcat](https://github.com/akopdev/nbcat) ⭐ 40 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-06-04 - Preview Jupyter notebooks (ipynb) in terminal.
* [treepp](https://github.com/terroo/treepp) ⭐ 34 | 🐛 1 | 🌐 C++ | 📅 2025-05-19 - The `tree` command with icons made with Modern C++.
* [lspp](https://github.com/terroo/lspp) ⭐ 31 | 🐛 1 | 🌐 C++ | 📅 2025-05-20 - An alternative to the `ls` command with display of icons of files and folders and with colors.
* [kat](https://github.com/terroo/kat) ⭐ 29 | 🐛 0 | 🌐 C++ | 📅 2025-06-10 - A `cat` command with syntax highlight, with support for several common programming languages.
* [meow](https://github.com/datsfilipe/meow) ⭐ 17 | 🐛 0 | 🌐 Lua | 📅 2025-12-14 - Uses Neovim text editor to print highlighted text in the terminal like cat, bat, etc., but using Neovim it allows to be more configurable, since it uses Lua.
* [Oyomu](https://github.com/EruEri/oyomu) ⭐ 15 | 🐛 0 | 📅 2025-06-08 - A command line comic reader and collection manager.
* [head-shoulders-knees-toes](https://github.com/jaggzh/head-shoulders-knees-toes) ⭐ 2 | 🐛 0 | 🌐 Perl | 📅 2025-04-05 - Preview file contents by sampling from head, middle, and end.
* [cacaview](http://caca.zoy.org/wiki/libcaca) - A library and a program to display JPG, PNG, GIF or BMP images in the terminal using ASCII characters.
* [mplayer](http://www.mplayerhq.hu/design7/news.html) - One of the most popular video/audio players around, plays most audio and video formats (using ASCII characters) in the shell, provides a GUI for graphical visualization.
* [mpv](https://mpv.io/) - A cross-platform media player with many features such as frame timing, MKV chapters and subtitles. It is a responsive video player with minimal layout customizable with themes. A good alternative media player to VLC since it can handle almost all the media formats as VLC, but using much less resources.
* [rttt](https://gitlab.com/BlackEdder/rttt) - A Hackernews, RSS and Reddit TUI reader written in C++.
* [TubiTui](https://codeberg.org/777/TubiTui.git) - A lightweight, libre, TUI-based YouTube client

## <a name="screensaver"></a>Screen savers

Screen savers with animations for the idle times of the computer.

* [gitlogue](https://github.com/unhappychoice/gitlogue) ⭐ 4,938 | 🐛 13 | 🌐 Rust | 📅 2026-08-16 - A cinematic Git commit replay tool for the terminal, turning your Git history into a living, animated story.
* [pipes.sh](https://github.com/pipeseroni/pipes.sh) ⭐ 3,013 | 🐛 14 | 🌐 Shell | 📅 2024-08-12 - Animated pipes terminal screensaver.
* [lifecycler](https://github.com/cxreiff/lifecycler) ⭐ 184 | 🐛 1 | 🌐 Rust | 📅 2025-05-22 - An aquarium that runs in your terminal.
* [sclocka](https://github.com/mezantrop/sclocka) ⭐ 37 | 🐛 0 | 🌐 C | 📅 2024-11-30 - The real screensaver/lock for terminals.
* [conway-screensaver](https://github.com/cdkw2/conway-screensaver) ⭐ 19 | 🐛 4 | 🌐 C | 📅 2024-10-26 - A Conways game of life screensaver for the terminal.
* [ASCII Saver](https://gitlab.com/mezantrop/ascsaver) - Screensaver for terminals.
* [termsaver](http://termsaver.brunobraga.net/) - termsaver to enjoy fancy ASCII screensavers like matrix, clock, starwars, and a couple of not-safe-for-work screens.

## <a name="screen-recorder"></a>Screen recorder

Tools to record the content of the terminal and manage the recording (e.g., converting into animated GIFs).

* [vhs](https://github.com/charmbracelet/vhs) ⭐ 20,706 | 🐛 170 | 🌐 Go | 📅 2026-08-24 - Write terminal GIFs as code for integration testing and demoing your CLI tools.
* [asciinema](https://github.com/asciinema/asciinema) ⭐ 17,720 | 🐛 8 | 🌐 Rust | 📅 2026-08-14 - Terminal session recorder.
* [terminalizer](https://github.com/faressoft/terminalizer) ⭐ 16,152 | 🐛 108 | 🌐 JavaScript | 📅 2024-08-29 - Record your terminal and generate animated GIF images or share a web player link [www.terminalizer.com](www.terminalizer.com).
* [termtosvg](https://github.com/nbedos/termtosvg) ⚠️ Archived - A Unix terminal recorder written in Python that renders your command line sessions as standalone SVG animations.
* [ttygif](https://github.com/icholy/ttygif) ⭐ 4,013 | 🐛 17 | 🌐 C | 📅 2025-08-02 - ttygif converts a ttyrec file into GIF files. It's a stripped down version of ttyplay that screenshots every frame.
* [ttystudio](https://github.com/chjj/ttystudio) ⭐ 3,237 | 🐛 20 | 🌐 JavaScript | 📅 2017-07-10 - Record your terminal and compile it to a GIF or APNG without any external dependencies, bash scripts, GIF concatenation, etc.
* [agg](https://github.com/asciinema/agg) ⭐ 1,703 | 🐛 5 | 🌐 Rust | 📅 2026-08-14 - agg is a command-line tool for generating animated GIF files from asciicast v2 files produced by `asciinema` terminal recorder.
* [t-rec](https://github.com/sassman/t-rec-rs) ⭐ 1,252 | 🐛 27 | 🌐 Rust | 📅 2026-08-10 - Blazingly fast terminal recorder that generates animated GIF images for the web written in rust.
* [rewindtty](https://github.com/debba/rewindtty) ⭐ 130 | 🐛 0 | 🌐 C | 📅 2026-02-11 - A terminal session recorder and replayer written in C that allows you to capture and replay terminal sessions with precise timing.
* [terminal-recorder](https://github.com/cortezcristian/terminal-recorder) ⭐ 111 | 🐛 1 | 🌐 JavaScript | 📅 2020-04-21 - Terminal recorder allows you to record your bash session, and export it to HTML so then you can share it with your friends.
* [goscript](https://github.com/elisescu/goscript) ⭐ 39 | 🐛 1 | 🌐 CSS | 📅 2024-08-21 - Goscript is a tool that records the terminal session (well, any command you run it with) and saves the output in a self contained HTML file that can be run in the browser, to playback the session.
* [terminal-svg-screenshot](https://github.com/suin/terminal-svg-screenshot) ⭐ 29 | 🐛 0 | 🌐 Nix | 📅 2025-06-21 - A tool for creating beautiful SVG screenshots of terminal output, perfect for documentation and blog posts.

# <a name="Security-and-Package-Management"></a>Security and Package Management

## <a name="crypto"></a>Ciphering and steganography

Programs to cipher data, streams and hide secrets in files.

* [SOPS](https://github.com/getsops/sops) ⭐ 22,909 | 🐛 443 | 🌐 Go | 📅 2026-08-24 - SOPS (Secrets OPerationS) is a simple and flexible tool for managing secrets, sops is an editor of encrypted files that supports YAML, JSON, ENV, INI and BINARY formats, encrypting the values but not the keys.
* [StegCloak](https://github.com/kurolabs/stegcloak) ⭐ 3,868 | 🐛 15 | 🌐 JavaScript | 📅 2024-10-01 - Hide secrets with invisible characters in plain text securely using passwords
* [Minisign](https://github.com/jedisct1/minisign) ⭐ 2,806 | 🐛 0 | 🌐 C | 📅 2026-05-11 - A dead simple tool to sign files and verify digital signatures.
* [ots](https://github.com/sniptt-official/ots) ⭐ 1,846 | 🐛 2 | 🌐 Go | 📅 2025-02-08 - Share end-to-end encrypted secrets with others via a one-time URL.
* [Image Steganography Tool](https://github.com/7thSamurai/steganography) ⭐ 1,085 | 🐛 1 | 🌐 C++ | 📅 2024-05-10 - Simple C++ Encryption and Steganography tool that uses Password-Protected-Encryption to secure a file's contents.
* [PaperAge](https://github.com/matiaskorhonen/paper-age) ⭐ 612 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - Easy and secure paper backups of secrets, which takes a text and generates an encrypted QR code to print on paper.
* [enc](https://github.com/life4/enc) ⭐ 519 | 🐛 0 | 🌐 Go | 📅 2025-11-12 - A modern and friendly CLI alternative to GnuPG: generate and download keys, encrypt, decrypt, and sign text and files, and more.
* [van-gonography](https://github.com/JoshuaKasa/van-gonography) ⭐ 449 | 🐛 0 | 🌐 Python | 📅 2025-11-09 - Hide your files of any type inside a image of your choice using steganography.
* [jdvrif](https://github.com/CleasbyCode/jdvrif) ⭐ 69 | 🐛 0 | 🌐 C++ | 📅 2026-08-24 - CLI tool to embed or extract files via a JPG image. Post and share your embedded JPG image on compatible sites.
* [eddy](https://github.com/70sh1/eddy) ⭐ 56 | 🐛 0 | 🌐 Go | 📅 2026-07-11 - Simple, fast CLI file encryption tool.
* [secret\_share](https://github.com/scosman/secret_share) ⭐ 25 | 🐛 2 | 🌐 Go | 📅 2026-08-21 - The program allows you to share messages (secrets and passwords) securely with a CLI.
* [cipher](https://github.com/ash-shell/cipher) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2017-06-22 - An Ash module that makes it easy to perform aes-256-cbc encryption for files and directories.
* [securo](https://github.com/iunary/securo) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-06-13 - Encrypt and decrypt files and folders using a symmetric encryption.
* [age](https://age-encryption.org/) - A simple, modern and secure encryption tool with small explicit keys, no config options, and UNIX-style composability.
* [cream](https://z3bra.org/cream/) - Encrypt and decrypt streams of data with only a master password. The key is derivated from the password + salt combo, and used to encrypt data byte per byte.
* [GnuPG](https://gnupg.org/) - GnuPG is a complete and free implementation of the OpenPGP standard as defined by RFC4880 (also known as PGP).
* [safe](https://z3bra.org/safe/) - Password protected secret keeper. Secrets are encrypted and stored on disk using a key derivated from your master password - no keys to manage.

## <a name="security"></a>Security

Encrypted file-systems and cyber-security tools.

* [feroxbuster](https://github.com/epi052/feroxbuster) ⭐ 8,032 | 🐛 44 | 🌐 Rust | 📅 2026-04-15 - A fast, simple, recursive content discovery tool written in Rust.
* [sandsifter](https://github.com/xoreaxeaxeax/sandsifter) ⭐ 5,071 | 🐛 64 | 🌐 Python | 📅 2024-02-20 - The x86 processor fuzzer.
* [wifi-password](https://github.com/rauchg/wifi-password) ⭐ 4,569 | 🐛 27 | 🌐 Shell | 📅 2024-06-13 - Get Wi-Fi pass.
* [SSH-Snake](https://github.com/MegaManSec/SSH-Snake) ⚠️ Archived - SSH-Snake is a self-propagating, self-replicating, file-less script that automates the post-exploitation task of SSH private key and host discovery.
* [acmetool](https://github.com/hlandau/acmetool) ⭐ 2,092 | 🐛 72 | 🌐 Go | 📅 2023-05-27 - Easy-to-use command line tool for automatically acquiring certificates from ACME servers (such as Let's Encrypt).
* [gpg-tui](https://github.com/orhun/gpg-tui) ⭐ 1,752 | 🐛 14 | 🌐 Rust | 📅 2026-08-10 - Manage your GnuPG keys with ease!
* [sshamble](https://github.com/runZeroInc/sshamble) ⭐ 1,180 | 🐛 0 | 🌐 Go | 📅 2026-07-28 - Unexpected exposures in SSH; the tool checks for several common weaknesses in SSH security issues.
* [vet](https://github.com/safedep/vet) ⭐ 1,102 | 🐛 99 | 🌐 Go | 📅 2026-08-24 - Tool for identifying risks in open source software supply chain.
* [OAuth2c](https://github.com/cloudentity/oauth2c) ⭐ 942 | 🐛 4 | 🌐 Go | 📅 2026-08-19 - A command-line tool for interacting with OAuth 2.0 authorization servers.
* [flawz](https://github.com/orhun/flawz) ⭐ 596 | 🐛 15 | 🌐 Rust | 📅 2026-06-13 - A Terminal UI for browsing security vulnerabilities (CVEs).
* [uacme](https://github.com/ndilieto/uacme) ⭐ 514 | 🐛 0 | 🌐 C | 📅 2026-07-07 - ACMEv2 client written in plain C with minimal dependencies.
* [cotp](https://github.com/replydev/cotp) ⭐ 385 | 🐛 5 | 🌐 Rust | 📅 2026-08-10 - Trustworthy, encrypted, command-line TOTP/HOTP authenticator app with import functionality.
* [pgen](https://github.com/ctsrc/Pgen) ⭐ 143 | 🐛 5 | 🌐 Rust | 📅 2026-04-22 - Generate passphrases using the wordlists for random passphrases made by the EFF.
* [fubar](https://github.com/irishmaestro/fubar) ⭐ 63 | 🐛 1 | 🌐 Rust | 📅 2024-10-09 - Formidable Unix Binary Arsenal and Repository. TUI built for offline payload generation, retrieval, and exfiltration.
* [pdvzip](https://github.com/CleasbyCode/pdvzip) ⭐ 63 | 🐛 0 | 🌐 C++ | 📅 2026-08-18 - CLI tool to embed a ZIP file within a PNG image to create a tweetable and "executable" PNG-ZIP polyglot file. Post & share your PNG-ZIP image on compatible sites.
* [keeenv](https://github.com/scross01/keeenv) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2026-06-22 - Command-line tool that populates environment variables from a local configuration file with encrypted Keepass database to dynamically fetch sensitive data.
* [encfs](http://www.arg0.net/#!encfs/c1awt) - Encrypted filesystem in user-space based on [FUSE](https://it.wikipedia.org/wiki/FUSE), mounts an encrypted directory into a clear one.
* [Firejail](https://firejail.wordpress.com/) - A SUID program that reduces the risk of security breaches by restricting the running environment of untrusted applications using Linux namespaces and seccomp-bpf.
* [gocryptfs](https://nuetzlich.net/gocryptfs) - An encrypted overlay filesystem written in Go.
* [grant](https://anchore.com/opensource/) - Grant is a tool for generating and managing license security policies for container images.
* [grype](https://anchore.com/opensource/) - Grype is a vulnerability scanner for container images and filesystems that supports a wide range of package managers.
* [hashcat](https://hashcat.net/hashcat/) - A robust and efficient password cracking tool that can help you recover lost passwords, audit password security, benchmark, or just figure out what data is stored in a hash.
* [Pareto Security](https://paretosecurity.com/linux) - Check for basic security hygiene of any Linux desktop.
* [quill](https://anchore.com/opensource/) - Simple mac binary signing from any platform.
* [syft](https://anchore.com/opensource/) - Syft is a CLI tool and library for generating a Software Bill of Materials (SBOM) from container images and filesystems.

## <a name="password-manager"></a>Password managers

Programs to store and manage collections of passwords and other login/authentication information.

* [teller](https://github.com/tellerops/teller) ⭐ 3,227 | 🐛 51 | 🌐 Rust | 📅 2026-01-27 - Cloud native secrets management for developers - never leave your command line for secrets.
* [rbw](https://github.com/doy/rbw) ⭐ 1,455 | 🐛 97 | 🌐 Rust | 📅 2025-12-31 - Unofficial command line client for Bitwarden that is “stateful”, i.e., it does not require the manual lock and unlock of the client.
* [passage](https://github.com/FiloSottile/passage) ⭐ 1,186 | 🐛 34 | 🌐 Shell | 📅 2024-08-30 - A fork of [password-store](https://www.passwordstore.org) that uses [age](https://age-encryption.org) as a backend instead of GnuPG.
* [pa](https://github.com/biox/pa) ⭐ 563 | 🐛 3 | 🌐 Shell | 📅 2026-07-21 - A simple password manager; encryption via age, written in portable POSIX shell.
* [SpicyPass](https://github.com/JFreegman/SpicyPass) ⭐ 371 | 🐛 4 | 🌐 C++ | 📅 2026-03-17 - A light-weight password manager with a focus on simplicity and security.
* [pash](https://github.com/dylanaraps/pash) ⚠️ Archived - A simple password manager using GPG written in POSIX sh.
* [oama](https://github.com/pdobsan/oama) ⭐ 256 | 🐛 10 | 🌐 Haskell | 📅 2025-08-29 - OAuth credential Manager.
* [Tlock](https://github.com/eklairs/tlock) ⭐ 201 | 🐛 7 | 🌐 Go | 📅 2024-09-01 - Two-Factor Authentication Tokens Manager in Terminal (Windows, Linux and MacOS).
* [keydex](https://github.com/shikaan/keydex) ⭐ 97 | 🐛 3 | 🌐 Go | 📅 2026-08-03 - Manage KeePass databases from your terminal.
* [hide](https://github.com/whatl3y/hide) ⭐ 61 | 🐛 17 | 🌐 TypeScript | 📅 2026-07-21 - AES-256 bit encrypted password manager with all encrypted passwords stored locally on your machine
* [kpxhs](https://github.com/akazukin5151/kpxhs) ⭐ 35 | 🐛 0 | 🌐 Haskell | 📅 2025-02-15 - Interactive KeePass database TUI viewer written in Haskell.
* [cpass](https://github.com/xlucn/cpass) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-08-10 - Another console UI for pass.
* [vault-crypt](https://github.com/DeadSwitch404/vault-crypt) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2025-07-18 - Minimalist GPG-powered vault encryption for KeePassXC. No cloud. No traces. Just your keys, your silence, and the seal.
* [tresor](https://github.com/Zaphoood/tresor) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2025-01-02 - A KeePass TUI written in Go using Bubble Tea.
* [pass](https://github.com/acidvegas/pass) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2026-04-22 - POSIX password manager that keeps passwords inside GPG encrypted files inside a simple directory tree.
* [safe.sh](https://github.com/windowsrefund/safe) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2019-09-11 - Pure Bash script to manage secure archives; simple and clean; uses [gnugpg](https://gnupg.org/) for encryption/decryption, thus can leverage tools like [GPG Agent](https://www.gnupg.org/documentation/manuals/gnupg/Invoking-GPG_002dAGENT.html).
* [VaultX](https://github.com/rhjddjdbc/vaultx) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2026-03-12 - Minimal script-based password manager for the command line; The program allows yout to manage multiple isolated vaults, use strong encryption, perform password breach checks, export QR codes.
* [Bitwarden CLI](https://bitwarden.com/help/cli/) - Command-line interface for Bitwarden, a multi-platform password manager targeted to companies and enterprises.
* dpg - The Deterministic Password Generator - Generates passwords based on a master password and the indication of the website/service/username, without the need of storing anything.
* [generate-pw](https://generatepw.org) - Randomly generate cryptographically-secure passwords.
* [gopass](https://www.gopass.pw/) - gopass is a rewrite of the pass password manager in Go with the aim of making it cross-platform and adding additional features. The target audience are professional developers and sysadmins (and especially teams of those) who are well versed with a command line interface.
* [kpcli](http://kpcli.sourceforge.net/) - A command line interface for KeePass databases.
* [passfzf](https://git.sr.ht/~mlaparie/passfzf) - A simple fzf wrapper for pass (the UNIX password-store). It allows fuzzy finding your pass passwords to copy, show, edit, delete, rename and duplicate them.
* [password-store](https://www.passwordstore.org/) - With pass, each password lives inside a GPG encrypted file whose filename is the title of the website or resource that requires the password. These encrypted files may be organized into meaningful folder hierarchies, copied from computer to computer, and, in general, manipulated using standard command line file management utilities.
* [titan](https://www.byteptr.com/titan/) - Password management belongs to the command line, deep into the Unix heartland, the shell. Titan is written in C and is available under the MIT license.

# <a name="Utilities-and-Miscellaneous"></a>Utilities and Miscellaneous

## <a name="utility"></a>Utilities

Miscellaneous utilities that are not do not fit in other categories and they are not numerous enough that they do not require a dedicated category.

* [Autocomplete](https://github.com/withfig/autocomplete) ⭐ 25,218 | 🐛 195 | 🌐 TypeScript | 📅 2025-05-05 - IDE-style autocomplete for your existing terminal & shell.
* [Keep](https://github.com/keephq/keep) ⭐ 12,241 | 🐛 572 | 🌐 Python | 📅 2026-08-24 - Simple alerting tool, with declarative syntax and builtin providers.
* [tickrs](https://github.com/tarkah/tickrs) ⭐ 1,683 | 🐛 33 | 🌐 Rust | 📅 2026-05-19 - Real-time ticker data in your terminal.
* [tmux-fingers](https://github.com/morantron/tmux-fingers) ⭐ 1,465 | 🐛 9 | 🌐 Crystal | 📅 2026-06-22 - Copy-pasting in terminal with vimium/vimperator like hints.
* [flog](https://github.com/mingrammer/flog) ⭐ 1,329 | 🐛 32 | 🌐 Go | 📅 2025-06-05 - A fake log generator for log formats such as apache-common, apache error and RFC3164 syslog.
* [Python re(gex)? exercises](https://github.com/learnbyexample/TUI-apps/tree/main/PyRegexExercises) ⭐ 1,014 | 🐛 0 | 🌐 Python | 📅 2026-02-02 - TUI application intended to help you practice Python regular expressions there are more than 100 exercises covering both the builtin re and third-party regex module.
* [envio](https://github.com/envio-cli/envio) ⭐ 989 | 🐛 13 | 🌐 Rust | 📅 2026-06-23 - Envio is a command-line tool that simplifies the management of environment variables across multiple profiles. It allows users to easily switch between different configurations and apply them to their current environment.
* [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) ⭐ 860 | 🐛 33 | 🌐 Shell | 📅 2026-07-31 - Tab completion using fzf.
* [gentoo-install](https://github.com/oddlama/gentoo-install) ⭐ 783 | 🐛 24 | 🌐 Shell | 📅 2026-08-08 - This project aspires to be your favorite way to install gentoo. It aims to provide a smooth installation experience, both for beginners and experts. You may configure it by using a menuconfig-inspired interface or simply via a config file.
* [Managarr](https://github.com/Dark-Alex-17/managarr) ⭐ 760 | 🐛 2 | 🌐 Rust | 📅 2026-07-06 - A TUI and CLI for managing your arr servers.
* [oji](https://github.com/xxczaki/oji) ⭐ 733 | 🐛 11 | 🌐 JavaScript | 📅 2026-04-30 - Interactive text emoji creator.
* [play](https://github.com/paololazzari/play) ⭐ 583 | 🐛 3 | 🌐 Go | 📅 2025-03-28 - TUI playground for your favorite programs, such as grep, sed and awk.
* [sisi](https://github.com/frost-beta/sisi) ⭐ 581 | 🐛 4 | 🌐 TypeScript | 📅 2024-09-16 - Semantic image search CLI tool.
* [config-file-validator](https://github.com/Boeing/config-file-validator) ⭐ 514 | 🐛 25 | 🌐 Go | 📅 2026-08-24 - Cross Platform tool to validate configuration files.
* [ProgressLine](https://github.com/kattouf/ProgressLine) ⭐ 204 | 🐛 1 | 🌐 Swift | 📅 2025-01-09 - Track commands progress in a compact one-line format.
* [movie](https://github.com/mayankchd/movie) ⭐ 175 | 🐛 1 | 🌐 JavaScript | 📅 2024-07-29 - A CLI for getting information about a movie and comparing two movies.
* [glyphs](https://github.com/maaslalani/glyphs) ⭐ 131 | 🐛 4 | 🌐 Go | 📅 2024-02-08 - Unicode symbols on the command line.
* [ttyscheme](https://github.com/kolunmi/ttyscheme) ⭐ 89 | 🐛 1 | 🌐 Shell | 📅 2026-02-24 - Collection of Color Schemes for the TTY.
* [bash-cache](https://github.com/dimo414/bash-cache) ⭐ 88 | 🐛 8 | 🌐 Shell | 📅 2023-01-05 - A function memoization / caching library for bash scripts and shells
* [sauce](https://github.com/cadecuddy/sauce) ⭐ 49 | 🐛 0 | 🌐 Go | 📅 2022-10-17 - A novelty CLI tool that identifies an anime from an image and yields key data about it.
* [sasqwatch](https://github.com/fabio42/sasqwatch) ⭐ 46 | 🐛 1 | 🌐 Go | 📅 2026-07-28 - A modern take on the classic watch command.
* [volgo](https://github.com/elliot40404/volgo) ⭐ 40 | 🐛 3 | 🌐 Go | 📅 2025-02-04 - A cross-platform CLI app written in Go for controlling system volume from the terminal. Use simple commands or a beautiful interactive TUI—even over SSH.
* [ccsum](https://github.com/sevenc-nanashi/ccsum) ⭐ 34 | 🐛 0 | 🌐 Rust | 📅 2026-06-24 - Convenient sha256sum (md5sum, sha1sum, and sha512sum) checksum with improved usability.
* [guesswidth](https://github.com/noborus/guesswidth) ⭐ 33 | 🐛 0 | 🌐 Go | 📅 2026-08-10 - Guess the width output without delimiters in commands that output to the terminal.
* [bashtutor](https://github.com/agvxov/bashtutor) ⭐ 31 | 🐛 0 | 🌐 Shell | 📅 2024-08-17 - Easily extendable utility to interactively showcase or teach CLIs, command line tasks, workflows and Bash itself.
* [anbu](https://github.com/tanq16/anbu) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2026-08-03 - A swiss army knife for CLI operations catered to devs and security professionals.
* [tab-pal](https://github.com/ben-n93/tab-pal) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2024-10-01 - A command-line app that makes it easier to add and edit custom colour palettes in Tableau.
* [Skylab](https://github.com/SerhiiStets/skylab) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2024-02-11 - A text user interface (TUI) tool that displays upcoming space launches in a user-friendly way.
* [Polykill](https://github.com/Bdeering1/polykill) ⭐ 19 | 🐛 2 | 🌐 Rust | 📅 2025-12-13 - Lightweight command line utility for removing dependencies and build artifacts from unused local projects.
* [Roku-tui](https://github.com/winsbe01/roku-cli) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2023-03-01 - A command line TUI remote for Roku.
* [Zsh Angel IQ System](https://github.com/psprint/zsh-angel-iq-system) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2023-04-28 - A bunch of intelligent extensions to Zsh, including an in-shell Ctags browser, an extension to Zinit plugin manager and Angel Swiss Knife.
* [Various Scripts](https://github.com/xkcd386at/scripts) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2026-05-26 - Various script, mainly in shell and Perl, to perform tasks such as combining head and tail, or other common tools accessed using fzf.
* [calm-garden-cli](https://github.com/jaroslaw-weber/calm-garden-cli) ⭐ 13 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-17 - A small, discreet terminal tool for breath exercises with progression: earn coins, buy plants, and upgrade your garden.
* [gtime](https://github.com/savitojs/gtime) ⭐ 11 | 🐛 2 | 🌐 Python | 📅 2026-08-12 - Python CLI utility for global time zone lookup, comparison, and management; The program supports fuzzy search, favorites, city comparison, meeting time conversion, and a live/watch mode.
* [sizeof](https://github.com/zackproser/sizeof) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2023-05-24 - Experimental CLI, written alongside ChatGPT4 and GitHub Copilot.
* [teetail](https://github.com/sl236/teetail) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2022-11-24 - Like tee, but only the tail goes in the file.
* [plzz](https://github.com/deep5050/plzz) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2023-08-15 - A Python CLI to automate daily tasks of both common and advanced users. It allows easily launching common and different types of operations such as creating random files or check hashes.
* [chet-client](https://github.com/Hillside-Labs/chet-client) ⭐ 4 | 🐛 4 | 🌐 Go | 📅 2024-01-02 - Measure your commands to speed up your development.
* [pangran](https://github.com/BimoT/pangran) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2023-06-04 - A simple TUI program that checks if you've typed a pangram.
* [ps1palette](https://github.com/WDoyle123/ps1palette) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-11-29 - Streamline Bash PS1 customization through script automation for prompt color coding and .bashrc integration.
* [sprinkles](https://github.com/KhalilOuali/sprinkles) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2023-07-18 - Randomly colors input text and outputs it to the terminal.
* [loopctl](https://github.com/Karvy-Singh/loopctl) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2025-07-27 - The program allows you to repeat a media/section of media x number of times and to repeat a certain part of media.
* [bkt](https://bkt.rs) - bkt is a subprocess caching utility that makes it easy to reuse past invocations of slow commands
* [DirCrcMd](https://gitlab.com/halanosiblee/dircrcmd.git) - Checksum directory in crc32 and export it into markdown.
* [mkdesk](https://gitlab.com/mr-draxs/mkdesk) - A program/command to create .desktop files (program launchers) using the terminal.
* [watch](http://www.linfo.org/watch.html) - Periodically runs a command in the console while temporarily clearing the screen content; it makes it easy to check differences between the output of two subsequent commands; it provides "diff" functionality to highlight the changing characters between outputs.

## <a name="weather"></a>Weather

Information about the weather, fetched from the Internet.

* [wego](https://github.com/schachmat/wego) ⭐ 8,537 | 🐛 16 | 🌐 Go | 📅 2026-08-01 - Weather app for the terminal.
* [tempy](https://github.com/noprobelm/tempy) ⭐ 194 | 🐛 4 | 🌐 Python | 📅 2024-03-07 - A simple, visually pleasing weather report in your terminal.
* [Raijin](https://github.com/MasonStooksbury/Raijin) ⭐ 172 | 🐛 2 | 🌐 Rust | 📅 2025-09-17 - A free, simple weather TUI that pulls data without the need for an API key, account, or subscription.
* [weather-cli](https://github.com/riyadhalnur/weather-cli) ⚠️ Archived - Check the weather for your city from the terminal.
* [gust](https://github.com/josephburgess/gust) ⭐ 30 | 🐛 1 | 🌐 Go | 📅 2026-04-13 - Command line weather app written in Go.
* [Aniweather](https://github.com/miselume/aniweather) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-01-08 - Aniweather is a simple console weather app featuring cute ASCII art of an anime girl.

# <a name="Learning-and-Leisure"></a>Learning and Leisure

## <a name="learning"></a>Learning and didactic tools

Programs that support learning and teaching about an argument.

* [GameShell](https://github.com/phyver/GameShell) ⭐ 3,162 | 🐛 11 | 🌐 Shell | 📅 2026-05-05 - GameShell was devised as a tool to help university students to engage with a real shell, in a way that encourages learning while also having fun.
* [TUI apps](https://github.com/learnbyexample/TUI-apps) ⭐ 1,014 | 🐛 0 | 🌐 Python | 📅 2026-02-02 - A repository containing a couple of one-script programs, mainly dedicated to training/learning CLI tools such as grep, awk, etc.
* [Countryfetch](https://github.com/nik-rev/countryfetch) ⭐ 281 | 🐛 5 | 🌐 Rust | 📅 2026-03-06 - A Command-line tool similar to Neofetch for obtaining information about your country.
* [lexy](https://github.com/antoniorodr/lexy) ⭐ 121 | 🐛 0 | 🌐 Python | 📅 2026-08-10 - Lexy is a lightweight CLI tool that fetches programming tutorials from "Learn X in Y Minutes" directly into your terminal. Quickly search, learn, and reference code examples without leaving your workflow.
* [minicloze](https://github.com/benmanone/minicloze) ⭐ 23 | 🐛 4 | 🌐 Rust | 📅 2026-08-20 - Rust-based command-line language-learning game using the Tatoeba database.
* [wb](https://github.com/MertGunduz/wb) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2023-09-01 - A TUI vocabulary notebook app for Linux based devices.
* [bashquest](https://github.com/toolleeo/bashquest) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2026-01-15 - Shell quest (Capture-The-Flag-style): a didactic game to train/teach common Unix shell commands.
* [bashmate](https://github.com/algobuddha/bashmate) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2025-07-08 - CLI tool to learn bash command with your natural language.
* [ShellKit](https://github.com/pokeyaro/shellkit) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-06-27 - Unix-like educational terminal toolkit consisting of: Libc (simulation of syscall, write, printf and more) and Pysh (interactive shell).

## <a name="flashcard"></a>Anki, decks and flashcards

Manage decks of flashcards and Anki decks.

* [flash-tui](https://github.com/TBS1996/speki) ⭐ 509 | 🐛 10 | 🌐 Rust | 📅 2024-12-22 - Flashcard app for the terminal.
* [speki](https://github.com/tbs1996/speki) ⭐ 509 | 🐛 10 | 🌐 Rust | 📅 2024-12-22 - Manage flashcards in the terminal similar to anki.
* [mdfc](https://github.com/bttger/markdown-flashcards) ⭐ 95 | 🐛 2 | 🌐 Go | 📅 2025-06-12 - Easily create and study flashcards using a Markdown file with spaced repetition.
* [GoCard](https://github.com/DavidMiserak/GoCard) ⭐ 58 | 🐛 12 | 🌐 Go | 📅 2026-05-15 - A lightweight file-based spaced repetition system (SRS) that uses plain Markdown files for flashcards. Perfect for developers who prefer text files, Git version control, and keyboard-driven interfaces.
* [hardv](https://github.com/dongyx/hardv) ⭐ 40 | 🐛 0 | 🌐 C | 📅 2026-04-15 - A CLI flashcard app for UNIX-compatible systems, conforming to the UNIX philosophy.
* [ToRRential Card processor](https://github.com/Constantin1489/trrc) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2023-06-17 - A command-line program to add a card to Anki using AnkiConnect API.
* [tui-deck](https://github.com/mebitek/tui-deck) ⭐ 23 | 🐛 1 | 🌐 Go | 📅 2024-02-25 - A TUI frontend for Nextcloud Deck app.
* [revise-tui](https://github.com/noelzubin/revise-tui) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2025-02-17 - A TUI Anki client. Revise is a command-line program used to schedule the review of items using spaced repetition.
* [py\_flashcards](https://github.com/M4THYOU/py_flashcards) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-04-19 - Text-only CLI flashcards parsed from Markdown file.
* [vocage](https://git.sr.ht/~proycon/vocage/) - Vocage is a minimalistic terminal-based vocabulary-learning tool. It presents flashcards using a spaced-repetition algorithm (e.g. Leitner). Data is stored in a simple plain-text tab-separated values format (TSV).

## <a name="typing"></a>Typing test and practice

Games and utilities to measure and/or improve the typing ability.

* [Smassh](https://github.com/kraanzu/smassh) ⭐ 2,040 | 🐛 11 | 🌐 Python | 📅 2026-08-17 - A TUI based typing test app inspired by MonkeyType.
* [ttyper](https://github.com/max-niederman/ttyper) ⭐ 1,589 | 🐛 35 | 🌐 Rust | 📅 2026-04-07 - Terminal-based typing test.
* [tt](https://github.com/lemnos/tt) ⭐ 924 | 🐛 40 | 🌐 Go | 📅 2024-05-16 - A terminal based typing test.
* [toipe](https://github.com/Samyak2/toipe) ⭐ 669 | 🐛 25 | 🌐 Rust | 📅 2024-06-10 - Yet another typing test, but crab flavored.
* [thokr](https://github.com/jrnxf/thokr) ⭐ 600 | 🐛 5 | 🌐 Rust | 📅 2026-06-12 - Sleek typing TUI with visualized results and historical logging.
* [typtea](https://github.com/ashish0kumar/typtea) ⭐ 242 | 🐛 2 | 🌐 Go | 📅 2026-02-20 - Minimal terminal-based typing speed tester with support for dozens of programming languages.
* [kboard](https://github.com/CamiloGarciaLaRotta/kboard) ⭐ 189 | 🐛 4 | 🌐 Go | 📅 2023-06-05 - Terminal game to practice keyboard typing.
* [Typon](https://github.com/ihsuy/Typon) ⭐ 99 | 🐛 2 | 🌐 C++ | 📅 2020-11-06 - A multi-featured typing practice tool which can turn any text file into a typing game.
* [ttypr](https://github.com/hotellogical05/ttypr) ⭐ 77 | 🐛 0 | 🌐 Rust | 📅 2026-03-21 - Terminal typing practice application.
* [typing-game-cli](https://github.com/akgondber/typing-game-cli) ⭐ 64 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-06 - Command line game to practice typing speed by competing against typer-robot or against your best result.
* [fasttyper](https://github.com/ickyicky/fasttyper) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2024-05-24 - Fasttyper is minimalistic typing test based on user provided exercising text.
* [typeinc](https://github.com/AnirudhG07/Typeinc) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2025-06-28 - An ncurses based terminal typing speed test with different difficulty levels and cool typing UI.
* [neotype](https://github.com/tteeoo/neotype) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2020-10-15 - A terminal-based typing game powered by classic ANSI escape codes.
* [LEARNTYPE](https://github.com/harkaitz/tcl-learntype) ⭐ 13 | 🐛 0 | 🌐 Tcl | 📅 2025-06-18 - Small CLI program for children (4/5 years old) to learn typing.
* [typist](https://github.com/wick3dr0se/typist) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2024-04-11 - A stupid simple type test written in pure Bash v5.1+.
* [Typ0](https://github.com/TusharIbtekar/go-typ0) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2025-06-23 - Interactive CLI tool for typing practice and speed tests built with Go and Bubble Tea.
* [termitype](https://github.com/emanuel2718/termitype) ⭐ 11 | 🐛 5 | 🌐 Rust | 📅 2026-03-02 - TUI typing game.
* [Typr](https://github.com/DriftingOtter/Typr) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-10-07 - `typr` is a Python-based application that utilizes the 'rich' module to provide you with a simple yet satisfying TUI when typing, `typr` is designed to be simple and easy to use.
* [typetype](https://github.com/ahmet8zer/typetype) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-08-06 - Minimalistic command line typing game.
* [chimp-type](https://github.com/NewstellerBot/chimp-type) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2025-01-20 - A minimal typing test for terminal written in go.
* [Typespeed](http://typespeed.sourceforge.net/) - Type words that are flying by from left to right as fast as you can; features different word sets, e.g., UNIX commands, English words, Non-English words.

## <a name="games"></a>Games

Board games, puzzles, roguelikes, role-play, adventures, card games, etc..

* [tinytetris](https://github.com/taylorconor/tinytetris) ⭐ 3,290 | 🐛 29 | 🌐 C++ | 📅 2024-07-09 - 80x23 terminal tetris game.
* [Pokete](https://github.com/lxgr-linux/pokete) ⭐ 3,148 | 🐛 31 | 🌐 Python | 📅 2026-05-22 - A terminal based Pokemon like game.
* [SSHTron](https://github.com/zachlatta/sshtron) ⭐ 2,490 | 🐛 12 | 🌐 Go | 📅 2023-07-17 - Multiplayer lightcycle game that runs through SSH.
* [awkaster](https://github.com/TheMozg/awk-raycaster) ⭐ 2,472 | 🐛 1 | 🌐 Awk | 📅 2023-01-20 - Pseudo-3D shooter written completely in gawk using raycasting technique.
* [rpg-cli](https://github.com/facundoolano/rpg-cli) ⭐ 1,679 | 🐛 6 | 🌐 Rust | 📅 2025-05-03 - Your filesystem as a dungeon!
* [Gameboy Emulator](https://github.com/gabrielrcouto/php-terminal-gameboy-emulator) ⭐ 1,610 | 🐛 6 | 🌐 PHP | 📅 2020-11-02 - A PHP Terminal GameBoy Emulator.
* [chess-tui](https://github.com/thomas-mauran/chess-tui) ⭐ 1,158 | 🐛 30 | 🌐 Rust | 📅 2026-08-17 - Play chess from your terminal.
* [Square Tic Tac Toe](https://github.com/learnbyexample/TUI-apps/tree/main/SquareTicTacToe) ⭐ 1,014 | 🐛 0 | 🌐 Python | 📅 2026-02-02 - A game like Tic Tac Toe, but you have to form a square with 4 corners instead of a line.
* [gambit](https://github.com/maaslalani/gambit) ⭐ 906 | 🐛 10 | 🌐 Go | 📅 2024-01-25 - Chess board in your terminal.
* [DOOM-ASCII](https://github.com/wojciech-graj/doom-ascii) ⭐ 878 | 🐛 0 | 🌐 C | 📅 2025-07-21 - Text-based DOOM running in terminal without sound.
* [rebels-in-the-sky](https://github.com/ricott1/rebels-in-the-sky) ⭐ 728 | 🐛 4 | 🌐 Rust | 📅 2026-08-19 - P2P terminal game about spacepirates playing basketball across the galaxy.
* [clidle](https://github.com/ajeetdsouza/clidle) ⭐ 633 | 🐛 2 | 🌐 Go | 📅 2025-03-28 - Wordle, now over SSH.
* [botany](https://github.com/jifunks/botany/) ⭐ 546 | 🐛 10 | 🌐 Python | 📅 2026-07-18 - A command line, realtime, virtual plant buddy.
* [terminal-doom](https://github.com/cryptocode/terminal-doom) ⭐ 436 | 🐛 2 | 🌐 C | 📅 2026-04-26 - Play DOOM in modern terminals.
* [nudoku](https://github.com/jubalh/nudoku) ⭐ 374 | 🐛 2 | 🌐 C | 📅 2026-07-08 - ncurses based sudoku game.
* [Solitaire TUI](https://github.com/brianstrauch/solitaire-tui) ⭐ 366 | 🐛 4 | 🌐 Go | 📅 2023-09-20 - Klondike solitaire for the terminal.
* [tty-solitaire](https://github.com/mpereira/tty-solitaire) ⭐ 358 | 🐛 24 | 🌐 C | 📅 2025-05-03 - Solitaire game for the terminal ncurses based.
* [cli-chess](https://github.com/trevorbayless/cli-chess) ⭐ 301 | 🐛 16 | 🌐 Python | 📅 2026-08-24 - A highly customizable way to play chess in your terminal. Play online (via Lichess.org) and offline against the Fairy-Stockfish engine. All Lichess variants are supported.
* [sssnake](https://github.com/AngelJumbo/sssnake) ⭐ 233 | 🐛 0 | 🌐 C | 📅 2026-07-31 - (Smart and sexy snake) The classic snake game for the terminal that can plays itself and be use like a screensaver.
* [nSnake](https://github.com/alexdantas/nSnake) ⭐ 228 | 🐛 23 | 🌐 C++ | 📅 2023-09-27 - The classic snake game in terminal with textual interface.
* [chs](https://github.com/nickzuber/chs) ⭐ 219 | 🐛 21 | 🌐 Python | 📅 2022-07-28 - Play chess against the Stockfish engine in your terminal.
* [Balatro TUI ](https://github.com/Passeriform/BalatroTUI) ⭐ 201 | 🐛 5 | 🌐 Rust | 📅 2026-05-01 - A minimal TUI clone of Balatro built in Rust.
* [Micro Tetris](https://github.com/troglobit/tetris) ⭐ 172 | 🐛 1 | 🌐 C | 📅 2025-06-22 - One of the smallest Tetris implementations in the world, utilizing only ANSI escape sequences to draw the board.
* [sshattrick](https://github.com/ricott1/sshattrick) ⭐ 147 | 🐛 2 | 🌐 Rust | 📅 2026-05-30 - Play Hattrick in your terminal over SSH.
* [snake](https://github.com/wick3dr0se/snake) ⭐ 115 | 🐛 2 | 🌐 Shell | 📅 2023-06-17 - A minimal TUI snake game written in pure BASH v5\_1+.
* [csol](https://github.com/nielssp/csol) ⭐ 114 | 🐛 0 | 🌐 C | 📅 2025-07-19 - Collection of solitaire/patience games, such as Klondike, FreeCell, Spider, and Yukon.
* [Moon-Buggy](https://github.com/seehuhn/moon-buggy) ⭐ 111 | 🐛 7 | 🌐 C | 📅 2025-11-17 - Game where you drive a car across the moon and jump over craters.
* [usolitaire](https://github.com/eliasdorneles/usolitaire) ⭐ 103 | 🐛 2 | 🌐 Python | 📅 2025-10-04 - Solitaire in your terminal.
* [Language-games](https://github.com/Hellisotherpeople/Language-games) ⭐ 97 | 🐛 0 | 🌐 Python | 📅 2026-04-09 - Dead simple games made with word vectors.
* [sku](https://github.com/fedeztk/sku) ⭐ 77 | 🐛 0 | 🌐 Go | 📅 2022-11-10 - Simple TUI written in go to play sudoku in the terminal.
* [Flapioca](https://github.com/kbrgl/flapioca) ⭐ 72 | 🐛 0 | 🌐 Go | 📅 2022-07-20 - A Flappy Bird-inspired terminal game written in Go.
* [asterion](https://github.com/ricott1/asterion) ⭐ 65 | 🐛 0 | 🌐 Rust | 📅 2026-05-30 - Find your way through an inifinite maze in this multiplayer ssh game. Beware of the minotaurs!
* [gg](https://github.com/Kaamkiya/gg) ⭐ 65 | 🐛 5 | 🌐 Go | 📅 2026-08-12 - A collection of games you can play in your terminal; written in Go.
* [terminal\_board\_games](https://github.com/salt-die/terminally_bored_terminal_board_games) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2022-07-15 - Board games for the terminal.
* [term-asteroids](https://github.com/NoiseByNorthwest/term-asteroids) ⭐ 57 | 🐛 2 | 🌐 PHP | 📅 2025-08-26 - An Asteroids-like game, running in a terminal, written in PHP.
* [go-sweep](https://github.com/maxpaulus43/go-sweep) ⭐ 55 | 🐛 0 | 🌐 Go | 📅 2023-12-29 - Minesweeper game in the command line programmed in Go.
* [2048-cli](https://github.com/Frost-Phoenix/2048-cli) ⭐ 48 | 🐛 1 | 🌐 C | 📅 2024-04-12 - A 2048 clone that run in the terminal.
* [mazter](https://github.com/Canop/mazter) ⭐ 45 | 🐛 0 | 🌐 Rust | 📅 2026-07-06 - A maze in your terminal.
* [Micro Snake](https://github.com/troglobit/snake) ⭐ 38 | 🐛 1 | 🌐 C | 📅 2023-04-16 - A small snake game, utilizing ANSI escape sequences to draw the board.
* [Cemetery Escape](https://github.com/tom-on-the-internet/cemetery-escape) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2023-11-19 - A game in which you must escape the cemetery. Search tombstones to find the key. Then head for the door, but watch out for ghosts.
* [Zigtris](https://github.com/ringtailsoftware/zigtris) ⭐ 33 | 🐛 0 | 🌐 Zig | 📅 2025-12-17 - Minimal terminal tetris game written in Zig.
* [sudoku-rs](https://github.com/MitchelPaulin/sudoku-rs) ⭐ 32 | 🐛 0 | 🌐 Rust | 📅 2024-08-17 - Sudoku game for the terminal, built with tui-rs.
* [Terminal Ping Pong](https://github.com/IshmamR/terminal.pong) ⭐ 32 | 🐛 0 | 🌐 Rust | 📅 2025-07-09 - A ping pong game in your terminal (play against AI opponent or a friend locally).
* [wordle-curses](https://github.com/knosmos/wordle-curses) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2022-02-07 - A simple TUI wordle game with curses.
* [rooshk](https://github.com/cmspeedrunner/rooshk) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2023-03-21 - A command line game in which you act as god over a sandbox world.
* [Brick Game emulator](https://github.com/ilyakurdyukov/brickgame-4bit) ⭐ 29 | 🐛 1 | 🌐 C | 📅 2024-05-11 - Brick Game emulator that uses 4-bit microcontroller from Holtek.
* [Dino](https://github.com/wldfngrs/chrome-dinosaur-terminal) ⭐ 26 | 🐛 0 | 🌐 C++ | 📅 2023-08-24 - A C++ and ncurses rendering of the popular chrome dinosaur game on the terminal.
* [minesweeper](https://github.com/gazpachoking/minesweeper) ⭐ 26 | 🐛 3 | 🌐 Python | 📅 2025-07-12 - Cross-platform terminal based minesweeper.
* [cheezee](https://github.com/detectivekaktus/cheezee) ⭐ 22 | 🐛 0 | 🌐 C | 📅 2024-07-09 - Chess TUI client built for Linux.
* [nchess](https://github.com/billyvinning/nchess) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2023-05-03 - Chess in the terminal, written in C (player vs player in the same terminal).
* [crappybird-py](https://github.com/JonPizza/crappybird-py) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2019-11-11 - Flappy bird.
* [terdle](https://github.com/neelkarma/terdle) ⭐ 19 | 🐛 0 | 🌐 Rust | 📅 2024-01-29 - Wordle implemented in Rust.
* [T-RexC](https://github.com/StiveMan1/T-RexC) ⭐ 17 | 🐛 0 | 🌐 C | 📅 2025-06-06 - Simple Console Google T-Rex Game.
* [Zoridor](https://github.com/ringtailsoftware/zoridor) ⭐ 16 | 🐛 0 | 🌐 Zig | 📅 2025-01-17 - Terminal and web version of the Quoridor board game for terminal and web.
* [DUNGEN!](https://github.com/derekburgess/dungen) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2025-07-05 - Creates dynamically a world of mistery, peril and unexpected discoveries (LLM generated labyrinths: your choices shape the story, the dangers you face and the secrets you uncover).
* [Noughts & Crosses (Tic Tac Toe)](https://github.com/vyalovvldmr/onx) ⭐ 15 | 🐛 4 | 🌐 Python | 📅 2022-10-06 - Noughts & Crosses client-server online game with your partner through websockets.
* [hangman](https://github.com/braheezy/hangman) ⭐ 13 | 🐛 1 | 🌐 Go | 📅 2022-09-18 - A Go TUI Hangman game built with the lovely BubbleTea framework.
* [shellphone](https://github.com/kokasmark/shellphone) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-01-18 - Terminal based Terraria player file editor.
* [Par Infinite Minesweeper](https://github.com/paulrobello/par_infini_sweeper) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2026-08-05 - Minesweeper TUI.
* [Words](https://github.com/ludovicianul/words) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2023-07-14 - A set of word-based puzzle games for the CLI while you wait for the build to run.
* [Terminal Roulette](https://github.com/levkush/TerminalRoulette) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2023-09-18 - Your own roulette table in the terminal.
* [terminordle](https://github.com/HP4k1h5/terminordle) ⭐ 9 | 🐛 1 | 🌐 TypeScript | 📅 2023-01-01 - Inspired by the popular online game wordle made, you can play a pretty close replica of the original locally or multiplayer over the network.
* [Durak](https://github.com/levkush/durak) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2023-10-18 - Durak card game for two in a terminal.
* [othello-cli](https://github.com/LelsersLasers/othello-cli) ⭐ 7 | 🐛 1 | 🌐 Rust | 📅 2024-08-28 - othello-cli is a CLI version of Othello (Reversi) written in Rust. You can play against another player, the AI, or watch two AIs play each other.
* [Sweeper](https://github.com/igor47/sweeper) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-04-30 - Basic ncurses Minesweeper game, wirtten in python, using curtsies library.
* [Maze of Me](https://github.com/bakill3/maze-of-me) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-09-02 - A deeply personal psychological game powered by AI and real user data.
* [nc2048](https://github.com/t0xk/nc2048) ⭐ 6 | 🐛 1 | 🌐 C | 📅 2023-04-12 - A ncurses 2048 game that can be played in the terminal.
* [dans-dungeon](https://github.com/ruscoe/dans-dungeon) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-04-26 - A dungeon crawler engine written in Python.
* [Minesweeper Game](https://github.com/omerkarabacak/minesweeper) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-09-08 - A small command line Minesweeper Game.
* [blackjack](https://github.com/acidvegas/blackjack) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-03-09 - IRC bot to play blackjack.
* [guess-word-cli](https://github.com/akgondber/guess-word-cli) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2024-05-19 - Find out a source word which characters was shuffled and moreover an extra character was added to bring some complexity.
* [NCurses Pacman](https://github.com/woodrowb96/ncurses-pacman) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2026-02-26 - Terminal-based Pac Man game written in c++.
* [CTetris++](https://github.com/Jejis06/CTetris/tree/master) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2025-06-08 - Feature-rich Tetris game written in C++ that runs in terminal with customizable visual styles and smooth gameplay.
* [word-blazer](https://github.com/mmed-hajnasr/word-blazer) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-02-25 - TUI labyrinth game that takes advantage of multiple graph algortihms.
* [Wordle](https://github.com/m-dango/raku-wordle/) ⭐ 2 | 🐛 2 | 🌐 Raku | 📅 2022-03-19 - Implementation of Wordle game hosted by The New York Times, written in Raku.
* [Bashtaker](https://github.com/EC2854/bashtaker) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-08-10 - Demake of Helltaker (videogame) written in bash.
* [escaping-figures-game-cli](https://github.com/akgondber/escaping-figures-game-cli) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2023-08-26 - Count figure's occurrences in the escaping figures matrix.
* [tetrs](https://github.com/Strophox/tetrs) ⚠️ Archived - Tetromino game engine and terminal application to play Tetris, written in Rust.
* [what-is-sequence-game](https://github.com/akgondber/what-is-sequence-game) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2025-02-25 - Game consisting in remembering sequence of appearing items and try to restore them in right order.
* [Angband](https://rephial.org/) - Angband is a free, single-player dungeon exploration game.
* [anonymine](https://oskog97.com/projects/anonymine/) - Curses mode minesweeper without guessing and other original features.
* [bastet](http://fph.altervista.org/prog/bastet.html) - (Bastard Tetris) implements the classical Tetris but with a logic to generate the next block which maximizes the difficulty for the player.
* [Brogue CE](https://sites.google.com/site/broguegame/) - Single-player strategy game set in the halls of a mysterious and randomly-generated dungeon.
* [Cataclysm: Dark Days Ahead](https://cataclysmdda.org/) - Open source turn-based survival RPG development project.
* [cli.poker](https://www.cli.poker) - Multiplayer Texas Hold'em poker played in the terminal over SSH. Just run `ssh cli.poker`.
* [Dwarf fortress](http://www.bay12games.com/dwarves/) - A fantasy game using ASCII art graphical representation of the game environment, it features a rich environment with many options and possibilities.
* [freesweep](http://www.upl.cs.wisc.edu/~hartmann/sweep/) - A Minesweeper clone for the terminal which allows you to configure settings such as table rows and columns up to 1024x1024!), percentage of bombs, colors, and also has a high scores table.
* [Frotz](https://davidgriffith.gitlab.io/frotz/) - Frotz is an interpreter for Infocom games and other Z-machine games.
* [greed](http://www.catb.org/~esr/greed/) - A game in which the goal is to move and consume all the numbers in a table.
* [MyMan](https://sourceforge.net/projects/myman/) - Video game for color and monochrome text terminals in the genre of Namco's Pac-Man.
* [Nethack](http://nethack.org/) - Single player rogue-like dungeon exploration game.
* [nInvaders](http://ninvaders.sourceforge.net/) - Game of Space Invaders for terminal.
* [Oldrunner](http://culot.org/public/Code/oldrunner.html) - Character-based remake of Lode Runner, includes all the original 150 levels.
* [Sausage](https://gitlab.com/christosangel/sausage) - Terminal word forming game, written in Bash, inspired by Bookworm.
* [Slash'EM](http://slashem.sourceforge.net/) - Rogue-like game derived from `nethack` offering extra features, monsters, and items; includes a GUI version.
* [Terminal Phase](https://dustycloud.org/blog/terminal-phase-1.0/) - A space shooter game you can play in your terminal.
* [tui-sudoku](https://gitlab.com/christosangel/tui-sudoku) - tui-sudoku is a configurable terminal interface sudoku game, with quite a few features.
* [tuifoop](https://gitlab.com/christosangel/tuifoop) - Terminal puzzle game with the goal of removing as many cells as possible (or even all cells) from a grid. A terminal clone of Swell Foop.
* [Wocogo](https://codeberg.org/kedlubnowski/wocogo) - Terminal word game that challenges players to combine given segments into existing words, uses rich library.
* [Wordle Solver](https://gitlab.com/christosangel/wordle-solver) - A bash script that can solve wordle riddles.

## <a name="funny"></a>Funny tools

Miscellaneous of tools that provide some funny/aesthetical functionality (animations, funny quotes, original message visualization, etc.).

* [hollywood](https://github.com/dustinkirkland/hollywood) ⭐ 3,234 | 🐛 3 | 🌐 Shell | 📅 2026-07-06 - Runs a script turning your Linux terminal into a Hollywood style real-time hacking terminal.
* [bucklespring](https://github.com/zevv/bucklespring) ⭐ 1,551 | 🐛 40 | 🌐 C | 📅 2025-08-24 - Emulates the sound of the old IBM Model-M space saver bucklespring keyboard while typing.
* [matrix-webcam](https://github.com/joschuck/matrix-webcam) ⭐ 1,490 | 🐛 0 | 🌐 Python | 📅 2022-10-05 - Take your video conference from within the matrix.
* [ponysay](https://github.com/erkin/ponysay) ⭐ 1,319 | 🐛 79 | 🌐 Pony | 📅 2024-08-14 - Pony rewrite of cowsay.
* [daktilo](https://github.com/orhun/daktilo) ⭐ 1,251 | 🐛 19 | 🌐 Rust | 📅 2026-08-17 - Turn your keyboard into a typewriter adding sounds at each keystroke.
* [boxes](https://github.com/ascii-boxes/boxes) ⭐ 683 | 🐛 0 | 🌐 C | 📅 2026-08-11 - Boxes is a command line filter program which draws ASCII art boxes around your input text.
* [Draw](https://github.com/maaslalani/draw) ⭐ 545 | 🐛 6 | 🌐 Go | 📅 2023-12-04 - draw is an simple drawing tool in the terminal. Hold your mouse down and move it across the screen to draw anything you want!
* [pyjokes](https://github.com/pyjokes/pyjokes) ⭐ 367 | 🐛 6 | 🌐 Python | 📅 2026-05-06 - One line jokes for programmers (jokes as a service).
* [pokeget](https://github.com/talwat/pokeget-rs) ⭐ 292 | 🐛 5 | 🌐 Rust | 📅 2026-07-13 - A bash script you can use to display cool sprites of Pokemon in your terminal.
* [kyun](https://github.com/file-acomplaint/kyun) ⭐ 274 | 🐛 0 | 🌐 Rust | 📅 2025-04-06 - Kyun is a low productivity, low fidelity, low customizablity text editor that has its focus firm on user discomfort.
* [yosay](https://github.com/yeoman/yosay) ⭐ 209 | 🐛 0 | 🌐 JavaScript | 📅 2025-02-07 - Like cowsay, but for yeoman.
* [Splash](https://github.com/joshi4/splash) ⭐ 123 | 🐛 10 | 🌐 Go | 📅 2026-04-06 - Program that adds color to your logs to make them easier to read.
* [chadsay](https://github.com/agvxov/chadsay) ⭐ 88 | 🐛 0 | 🌐 Shell | 📅 2025-05-16 - Like cowsay, but pronounced by GigaChad.
* [Russhian Roulette](https://github.com/cyradotpink/russhian-roulette) ⭐ 88 | 🐛 0 | 🌐 JavaScript | 📅 2024-06-03 - 1/6 chance of posting your SSH private key on pastebin (do you really want to try?).
* [clouddrift](https://github.com/thrly/clouddrift) ⭐ 19 | 🐛 2 | 🌐 JavaScript | 📅 2025-01-24 - Soft clouds drifting across your terminal.
* [Limoji](https://github.com/GEROGIANNIS/Limoji) ⭐ 19 | 🐛 5 | 🌐 Shell | 📅 2022-12-26 - Limoji is an open source tool that makes it easy to choose between hundreds of cool ASCII emoticons and share them with your friends.
* [HARRY\_POTTER\_ALIASES](https://github.com/P-Y-R-O-B-O-T/HARRY_POTTER_ALIASES) ⭐ 18 | 🐛 0 | 📅 2024-05-20 - Harry Potter-themed aliases a magical journey through the wizarding world of terminal commands.
* [bollywood](https://github.com/abloch/bollywood) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2026-04-22 - Runs terminal screencasts in multiple panes, resulting in another real-time Hollywood-style real-time hacking terminal.
* [ting](https://github.com/dhth/ting) ⭐ 9 | 🐛 1 | 🌐 Rust | 📅 2026-06-19 - The program provides audio feedback on the command line.
* [chuckle-cli](https://github.com/seburbandev/chuckle-cli) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2024-08-24 - An application that utilises an API in order to print out jokes in your terminal.
* [cowsay](https://en.wikipedia.org/wiki/Cowsay) - Generate an ASCII art of a cow with a bubble containing the specified message (I provide the Wikipedia link since at the moment the link to the author's homepage results to be unreachable).
* [cowthink](https://en.wikipedia.org/wiki/Cowsay) - Same as `cowsay`, but uses a "think" bubble instead of a speech bubble.
* [fortune](http://software.clapper.org/fortune/) - Generates random messages fetched from a quotation database.

## <a name="religion"></a>Religion

Tools to handle religious material, e.g. reading the Holy Bible.

* [bible](https://github.com/BibleJS/BibleApp) ⭐ 340 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-06 - Read the Holy Bible via the command line.
* [bbl](https://github.com/nehemiaharchives/bbl) ⭐ 97 | 🐛 5 | 🌐 Kotlin | 📅 2026-07-11 - Read, search Holy Bible in command line.
* [Bible TUI](https://github.com/terroo/bible-tui) ⭐ 35 | 🐛 0 | 🌐 C++ | 📅 2025-06-27 - Displays dynamic or selected verses from the Bible with different frames and colore themes.
* [CatenaVetus](https://github.com/jimbob88/CatenaVetus) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2026-08-21 - A TUI for reading the Church Fathers.
* [ltorah](https://github.com/Mandrew0822/ltorah) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2024-01-13 - ltorah provides a way to read the ancient hebrew Torah from the command line.
* [The Rock](https://gitlab.com/NoahJelen/the-rock) - Command line King James bible viewer for Linux systems modeled after Debian's bible-kjv, but with extra features.

## <a name="science"></a>Science

Packages for scientific research and science applications, e.g., bibliography and publication management.

* [starfetch](https://github.com/Haruno19/starfetch) ⭐ 362 | 🐛 3 | 🌐 C++ | 📅 2025-12-01 - Command line tool that displays constellations.
* [periodic-table-cli](https://github.com/spirometaxas/periodic-table-cli) ⭐ 304 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-03 - An interactive Periodic Table of Elements app for the console!
* [Pubs](https://github.com/pubs/pubs) ⭐ 293 | 🐛 69 | 🌐 Python | 📅 2024-06-01 - Pubs organizes your scientific papers together with their bibliographic data and provides command line access to basic and advanced manipulation of your library.
* [conrad](https://github.com/vinayak-mehta/conrad) ⭐ 254 | 🐛 37 | 🌐 Python | 📅 2026-08-24 - Track conferences and meetups.
* [ptable](https://github.com/velorek1/ptable) ⭐ 145 | 🐛 1 | 🌐 C | 📅 2025-08-01 - A beautiful TUI periodic table for GNU/Linux terminals.
* [terminalperiodictable](https://github.com/velorek1/terminalperiodictable) ⭐ 145 | 🐛 1 | 🌐 C | 📅 2025-08-01 - Periodic table TUI for GNU/linux systems coded in C with no extra dependencies.
* [oeis-tui](https://github.com/hako/oeis-tui) ⭐ 91 | 🐛 0 | 🌐 Rust | 📅 2026-02-03 - A TUI and CLI for browsing the On-Line Encyclopedia of Integer Sequences (OEIS) in the terminal.
* [element](https://github.com/gennaro-tedesco/element) ⭐ 84 | 🐛 0 | 🌐 Go | 📅 2022-10-31 - Periodic table on the command line.
* [bib.awk](https://github.com/huijunchen9260/bib.awk) ⭐ 76 | 🐛 0 | 🌐 Awk | 📅 2025-09-01 - Bibliography manager written in awk.
* [periodic-table-cli-py](https://github.com/spirometaxas/periodic-table-cli-py) ⭐ 51 | 🐛 1 | 🌐 Python | 📅 2025-09-07 - An interactive Periodic Table of Elements app for the console.
* [pt.sh](https://github.com/alexeytal/pt.sh) ⭐ 29 | 🐛 0 | 🌐 Shell | 📅 2022-09-11 - CLI periodic table with search and many properties.
* [Physics TUI](https://github.com/ClaudioRMalvino/physics_TUI) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-07-09 - TUI for physics reference and calculations, providing interactive access to physics equations, definitions, and calculator organized by chapter.
* [papis](https://github.com/alejandrogallo/papis) ⭐ 27 | 🐛 0 | 🌐 HTML | 📅 2023-09-16 - Extensible document and bibliography manager.
* [bibtools](https://github.com/pkgw/bibtools) ⭐ 15 | 🐛 13 | 🌐 Python | 📅 2026-07-30 - Command-line bibliography manager.
* [slr-kit](https://github.com/robolab-pavia/slr-kit) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-07-27 - Set of CLI tools to assist the writing of Systematic Literature Reviews powered by Natural Language Processing.
* [GCTU](https://github.com/Mandrew0822/GCTU---Genetic-code-translation-utility) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2023-03-28 - A simple command line tool which allows one to convert DNA code sequences to the different RNA sequences.
* [FAWOC](https://github.com/robolab-pavia/fawoc) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2023-03-27 - FAWOC is a TUI program for manually labelling a list of words. It has been developed to support the efficient clustering of documents based on topic modeling algorithms such as Dirichlet Latent Allocation.
* [Bibiman](https://codeberg.org/lukeflo/bibiman) - A TUI for fast and simple interacting with your BibLaTeX database.
* [BibMan](https://ductri.github.io/note/2023/09/27/bibman.html) - A TUI bibliography manager. It aims to support only the most basis features as a general bibliography manager.
* [cobib](https://gitlab.com/mrossinek/cobib) - Simple, command-line based bibliography management tool.
* [scholarref](https://adamsgaard.dk/scholarref.html) - Tools to never deal with journal webpages again.

# <a name="resources"></a>Related resources

A list of some online resources that contribute interesting links to apps and info.

[Awesome Modern CLI](https://github.com/thegdsks/awesome-modern-cli/) ⭐ 412 | 🐛 6 | 📅 2026-07-13 - A curated list of modern alternatives to classic command-line tools. Faster, prettier, smarter replacements for the Unix utilities you use every day.

[The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) ⭐ 162,163 | 🐛 257 | 📅 2024-06-25 - A wonderful summary from Joshua Levy regarding command line (Bash in particular) tools, programs, tips, and tricks; contains many pointers to resources and repositories, in the form of "to do this you must know that", which gives great pointers but requires further investigation from different sources; translated in many languages.

[Inconsolation blog](https://inconsolation.wordpress.com/) - "Adventures with lightweight and minimalist software for Linux": reviews of many command-line programs; many programs reviewed (400+, at least), with screenshots and animated GIFs; the style of presentation is ironic and funny, but requires some effort to figure out the real contribution of a program.

[A little collection of cool unix terminal/console/curses tools](https://kkovacs.eu/cool-but-obscure-unix-tools) - "Some are little-known, some are just too useful to miss, some are pure obscure..." from Kristof Kovacs; nice list with screenshot; mostly oriented to system administration; unfortunately there are no clickable links.

[Caleb Xu shell awesome](https://github.com/alebcay/awesome-shell) ⭐ 37,501 | 🐛 184 | 📅 2025-08-28 - Focused on UNIX shell tools.

[Adam Harris awesome CLI apps](https://github.com/aharris88/awesome-cli-apps) ⭐ 20,238 | 🐛 1 | 🌐 Shell | 📅 2026-08-22 - Nice list of tools; somehow too much JavaScript/Node.js-centered for my tastes.

[Marcel Bischoff awesome commandd line apps](https://github.com/herrbischoff/awesome-command-line-apps) ⚠️ Archived - Nice up-to-date list of useful tools.

[Awesome CLI by sintaxi](https://github.com/sintaxi/awesome-cli) ⭐ 53 | 🐛 5 | 📅 2019-08-09 - Relatively short list with short descriptions; with some original entries.

[awesome-ttygames](https://ligurio.github.io/awesome-ttygames/) - Large awesome list of terminal games. The collection is maintained in a YAML format. Each item contains a description and an optional screencast.

[Site Generators](https://jamstack.org/generators/) - A comprehensive list of Static Site Generators.

[Awesome git addons](https://github.com/stevemao/awesome-git-addons) ⭐ 2,194 | 🐛 15 | 📅 2024-10-15 - A curated list of add-ons that extend/enhance the git CLI.

[Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) ⭐ 13,088 | 🐛 148 | 🌐 Shell | 📅 2024-07-26 - A curated list of Terminal frameworks, plugins & resources for CLI lovers.

[Awesome Terminal Recorder](https://github.com/orangekame3/awesome-terminal-recorder) ⭐ 254 | 🐛 1 | 📅 2026-05-05 - Curated list of outstanding terminal Recorder that make your day brighter! Each item is associated with an animated GIF that shows some examples of usage.

[commandlinefu.com](https://www.commandlinefu.com/commands/browse) - The place to record those command-line gems that you return to again and again. That way others can gain from your CLI wisdom and you from theirs too.

[cli.club](https://cli.club/) - A collection of the best CLI/ncurses software covering a wide range of categories from messaging, music, text editing and more.

[texteditors.org](https://texteditors.org/cgi-bin/wiki.pl?search=HomePage) - A huge collection of links to resources on text editor. It contains references to non-CLI programs.

[Terminal Trove](https://terminaltrove.com/) - Collection of terminal CLI/TUI programs, with one page per program, nice screenshots and animated GIFs.

[Terminal Directory](https://termui.sh/) - List of all (known) terminals.

[Awesome TUIs](https://github.com/rothgar/awesome-tuis) ⭐ 20,311 | 🐛 83 | 📅 2026-08-11 - An awesome list dedicated to TUI programs.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
