<table>
    <tr>
        <td>License</td>
        <td><img src='https://img.shields.io/pypi/l/latex2mathml.svg?style=for-the-badge' alt="License"></td>
        <td>Version</td>
        <td><img src='https://img.shields.io/pypi/v/latex2mathml.svg?logo=pypi&style=for-the-badge' alt="Version"></td>
    </tr>
    <tr>
        <td>Github Actions</td>
        <td><img src='https://img.shields.io/github/actions/workflow/status/roniemartinez/latex2mathml/python.yml?branch=master&label=actions&logo=github%20actions&style=for-the-badge' alt="Github Actions"></td>
        <td>Coverage</td>
        <td><img src='https://img.shields.io/codecov/c/github/roniemartinez/latex2mathml/master?label=codecov&logo=codecov&style=for-the-badge' alt="CodeCov"></td>
    </tr>
    <tr>
        <td>Supported versions</td>
        <td><img src='https://img.shields.io/pypi/pyversions/latex2mathml.svg?logo=python&style=for-the-badge' alt="Python Versions"></td>
        <td>Wheel</td>
        <td><img src='https://img.shields.io/pypi/wheel/latex2mathml.svg?style=for-the-badge' alt="Wheel"></td>
    </tr>
    <tr>
        <td>Status</td>
        <td><img src='https://img.shields.io/pypi/status/latex2mathml.svg?style=for-the-badge' alt="Status"></td>
        <td>Downloads</td>
        <td><img src='https://img.shields.io/pypi/dm/latex2mathml.svg?style=for-the-badge' alt="Downloads"></td>
    </tr>
    <tr>
        <td>All Contributors</td>
        <td><a href="#contributors-"><img src='https://img.shields.io/github/all-contributors/roniemartinez/latex2mathml?style=for-the-badge' alt="All Contributors"></a></td>
    </tr>
</table>

# latex2mathml

Pure Python library for LaTeX to MathML conversion

## Installation

```bash
pip install latex2mathml
```

## Usage

### Python

```python
import latex2mathml.converter

latex_input = "<your_latex_string>"
mathml_output = latex2mathml.converter.convert(latex_input)
```

### Command-line

```shell
% latex2mathml -h
usage: latex2mathml [-h] [-V] [-b] [-t TEXT | -f FILE | -s]

Pure Python library for LaTeX to MathML conversion

options:
  -h, --help            show this help message and exit
  -V, --version         Show version
  -b, --block           Display block

required arguments:
  -t TEXT, --text TEXT  Text
  -f FILE, --file FILE  File
  -s, --stdin           Stdin
```

## References
### LaTeX

- https://en.wikibooks.org/wiki/LaTeX/Mathematics
- http://artofproblemsolving.com/wiki/index.php?title=Main_Page
- http://milde.users.sourceforge.net/LUCR/Math/
- https://math-linux.com/latex-26/faq/latex-faq/article/latex-derivatives-limits-sums-products-and-integrals
- https://www.tutorialspoint.com/tex_commands
- https://www.giss.nasa.gov/tools/latex/ltx-86.html
- https://ftp.gwdg.de/pub/ctan/info/l2tabu/english/l2tabuen.pdf

### Gotchas

Note that when opening a `\begin{align*}` you must use `align*` there is no support for the regular `\begin{align}`

### MathML

- http://www.xmlmind.com/tutorials/MathML/


## Author

- [Ronie Martinez](mailto:ronmarti18@gmail.com)

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://ron.sh"><img src="https://avatars.githubusercontent.com/u/2573537?v=4?s=100" width="100px;" alt="Ronie Martinez"/><br /><sub><b>Ronie Martinez</b></sub></a><br /><a href="#maintenance-roniemartinez" title="Maintenance">🚧</a> <a href="https://github.com/roniemartinez/latex2mathml/commits?author=roniemartinez" title="Code">💻</a> <a href="#infra-roniemartinez" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://anwen.cc/"><img src="https://avatars.githubusercontent.com/u/1472850?v=4?s=100" width="100px;" alt="askender"/><br /><sub><b>askender</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/commits?author=askender" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/06180339"><img src="https://avatars.githubusercontent.com/u/25408501?v=4?s=100" width="100px;" alt="06180339"/><br /><sub><b>06180339</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/commits?author=06180339" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/chaihahaha"><img src="https://avatars.githubusercontent.com/u/24356676?v=4?s=100" width="100px;" alt="chaihahaha"/><br /><sub><b>chaihahaha</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/commits?author=chaihahaha" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/huangradio"><img src="https://avatars.githubusercontent.com/u/63624395?v=4?s=100" width="100px;" alt="HQY"/><br /><sub><b>HQY</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Ahuangradio" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Sun-ZhenXing"><img src="https://avatars.githubusercontent.com/u/44517244?v=4?s=100" width="100px;" alt="鸭梨"/><br /><sub><b>鸭梨</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3ASun-ZhenXing" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/oliverstefanov"><img src="https://avatars.githubusercontent.com/u/33491656?v=4?s=100" width="100px;" alt="oliverstefanov"/><br /><sub><b>oliverstefanov</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Aoliverstefanov" title="Bug reports">🐛</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ghost"><img src="https://avatars.githubusercontent.com/u/10137?v=4?s=100" width="100px;" alt="Deleted user"/><br /><sub><b>Deleted user</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Aghost" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/cesaryuan"><img src="https://avatars.githubusercontent.com/u/35998162?v=4?s=100" width="100px;" alt="Cesaryuan"/><br /><sub><b>Cesaryuan</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Acesaryuan" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/tonystank3000"><img src="https://avatars.githubusercontent.com/u/6315974?v=4?s=100" width="100px;" alt="TonyStank"/><br /><sub><b>TonyStank</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Atonystank3000" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://polarwinkel.de"><img src="https://avatars.githubusercontent.com/u/1512713?v=4?s=100" width="100px;" alt="Dirk Winkel"/><br /><sub><b>Dirk Winkel</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Apolarwinkel" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/sinslu"><img src="https://avatars.githubusercontent.com/u/12248270?v=4?s=100" width="100px;" alt="sinslu"/><br /><sub><b>sinslu</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Asinslu" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://ubavic.rs"><img src="https://avatars.githubusercontent.com/u/53820106?v=4?s=100" width="100px;" alt="Nikola Ubavić"/><br /><sub><b>Nikola Ubavić</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Aubavic" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/abhisheksia"><img src="https://avatars.githubusercontent.com/u/68808662?v=4?s=100" width="100px;" alt="abhisheksia"/><br /><sub><b>abhisheksia</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Aabhisheksia" title="Bug reports">🐛</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://denissalem.tuxfamily.org"><img src="https://avatars.githubusercontent.com/u/4476506?v=4?s=100" width="100px;" alt="Denis Salem"/><br /><sub><b>Denis Salem</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3ADenisSalem" title="Bug reports">🐛</a> <a href="https://github.com/roniemartinez/latex2mathml/commits?author=DenisSalem" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://clontz.org"><img src="https://avatars.githubusercontent.com/u/1559632?v=4?s=100" width="100px;" alt="Steven Clontz"/><br /><sub><b>Steven Clontz</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3AStevenClontz" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/yuwenjun1"><img src="https://avatars.githubusercontent.com/u/43265090?v=4?s=100" width="100px;" alt="空白"/><br /><sub><b>空白</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Ayuwenjun1" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/amuramatsu"><img src="https://avatars.githubusercontent.com/u/6500918?v=4?s=100" width="100px;" alt="MURAMATSU Atshshi"/><br /><sub><b>MURAMATSU Atshshi</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Aamuramatsu" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/leingang"><img src="https://avatars.githubusercontent.com/u/570942?v=4?s=100" width="100px;" alt="leingang"/><br /><sub><b>leingang</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Aleingang" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Nigel-Amers"><img src="https://avatars.githubusercontent.com/u/14248498?v=4?s=100" width="100px;" alt="Nigel Amers"/><br /><sub><b>Nigel Amers</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3ANigel-Amers" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/retsyo"><img src="https://avatars.githubusercontent.com/u/7960913?v=4?s=100" width="100px;" alt="retsyo"/><br /><sub><b>retsyo</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Aretsyo" title="Bug reports">🐛</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/miakramer"><img src="https://avatars.githubusercontent.com/u/16845265?v=4?s=100" width="100px;" alt="Mia Kramer"/><br /><sub><b>Mia Kramer</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/commits?author=miakramer" title="Code">💻</a> <a href="https://github.com/roniemartinez/latex2mathml/commits?author=miakramer" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://cnx.gdn"><img src="https://avatars.githubusercontent.com/u/13689192?v=4?s=100" width="100px;" alt="Nguyễn Gia Phong"/><br /><sub><b>Nguyễn Gia Phong</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3AMcSinyx" title="Bug reports">🐛</a> <a href="https://github.com/roniemartinez/latex2mathml/commits?author=McSinyx" title="Code">💻</a> <a href="https://github.com/roniemartinez/latex2mathml/commits?author=McSinyx" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://cdelker.github.io"><img src="https://avatars.githubusercontent.com/u/44102190?v=4?s=100" width="100px;" alt="Collin Delker"/><br /><sub><b>Collin Delker</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Acdelker" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jiotv321"><img src="https://avatars.githubusercontent.com/u/118644533?v=4?s=100" width="100px;" alt="jiotv321"/><br /><sub><b>jiotv321</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/issues?q=author%3Ajiotv321" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/felixonmars"><img src="https://avatars.githubusercontent.com/u/1006477?v=4?s=100" width="100px;" alt="Felix Yan"/><br /><sub><b>Felix Yan</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/commits?author=felixonmars" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://rob-blackbourn.github.io/blog/"><img src="https://avatars.githubusercontent.com/u/2880305?v=4?s=100" width="100px;" alt="Rob Blackbourn"/><br /><sub><b>Rob Blackbourn</b></sub></a><br /><a href="https://github.com/roniemartinez/latex2mathml/commits?author=rob-blackbourn" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
