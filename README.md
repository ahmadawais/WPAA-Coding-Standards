<h1 align="center">
  <img src="https://on.ahmda.ws/rwYc/c" />

  WPAA-Coding-Standards
</h1>


<br>

[![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](https://github.com/ahmadawais/wpaa-coding-standards) [![Tweet for help](https://img.shields.io/twitter/follow/mrahmadawais.svg?style=social&label=Tweet%20@MrAhmadAwais)](https://twitter.com/mrahmadawais/) [![GitHub stars](https://img.shields.io/github/stars/ahmadawais/wpaa-coding-standards.svg?style=social&label=Stars)](https://github.com/ahmadawais/wpaa-coding-standards/stargazers) [![GitHub followers](https://img.shields.io/github/followers/ahmadawais.svg?style=social&label=Follow)](https://github.com/ahmadawais?tab=followers)

<table width='100%' align="center">
    <tr>
        <td align='left' width='100%' colspan='2'>
            <strong><code>WPAA-Coding-Standards</code></strong><br />
            Custom linting and coding standards for WordPress with VSCode.
        </td>
    </tr>
    <tr>
        <td>
            A FOSS (Free & Open Source Software) project developed by <a href='https://github.com/ahmadawais'>Ahmad Awais</a>.
        </td>
        <td align='center'>
            <a href='https://AhmadAwais.com/'>
                <img src='https://i.imgur.com/Asg4d3k.png' width='100' />
            </a>
        </td>
    </tr>
    <tr><td><sup> Follow Ahmad's #FOSS work on GitHub <a href='https://github.com/ahmadawais'>@AhmadAwais</a> —   Say Hi on Twitter <a href="https://twitter.com/mrahmadawais/">@MrAhmadAwais</a></sup></td><td  align='center'>👋</td></tr>
</table>
<br>
# Custom WordPress Coding Standards by Ahmad Awais

Custom linting and coding standards for WordPress with VSCode.

![Start](https://on.ahmda.ws/osd3/c)

## GETTING STARTED!

For having these standards you need to install a couple of things like Composer, PHPCS, WordPress Coding Standards. Run the following commands.

```sh
# Make ~/bin dir.
cd ~ && mkdir -p bin && cd bin

# Download Composer.
curl -s http://getcomposer.org/installer | php

# Clone PHPCS, WPCS, and this repo.
git clone https://github.com/squizlabs/PHP_CodeSniffer.git phpcs
git clone -b master https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards.git wpcs
git clone https://github.com/ahmadawais/wpaa-coding-standards.git wpaa

# Install composer, phpcs, and phpcbf.
sudo ln -s ~/bin/composer.phar /usr/local/bin/composer
sudo ln -s ~/bin/phpcs/bin/phpcs /usr/local/bin/phpcs
sudo ln -s ~/bin/phpcs/bin/phpcbf /usr/local/bin/phpcbf

# Set phpcs configuration for wpcs and wpaa.
phpcs --config-set installed_paths /Users/$USER/bin/wpaa/WPAA,/Users/$USER/bin/wpcs
```

And then go to VSCode, install [phpcs](https://marketplace.visualstudio.com/items?itemName=ikappas.phpcs) extension and then go to settings <kbd>⌘</kbd> + <kbd>,</kbd> and add the following settings. Finally reload.

```json
// Setting for phpcs.
"phpcs.executablePath": "/usr/local/bin/phpcs",
"phpcs.standard": "WPAA",
```


<br>

#### **Hello, we're [TheDevCouple](https://TheDevCouple.com)**!

I ([Ahmad Awais](https://twitter.com/mrahmadawais/)) am a Full Stack Web Developer and a regular core contributor at WordPress. My significant other ([Maedah Batool](https://twitter.com/MaedahBatool/)) is a Technical Project Manager, and she's also a WordPress Core Contributor. Together with our [team](https://WPCouple.com/team), we run the [TheDevCouple.com](https://TheDevCouple.com/).

If you'd like to get insights into our love for open source software, professional full stack development, WordPress community, the growth of JavaScript or growing a family, building, and bootstrapping a business, then subscribe to our premium newsletter called ↣ [The WordPress Takeaway](https://WPTakeaway.club)!

#### [**Support our Open Source Projects!**](https://pay.paddle.com/checkout/515568) 🎩

If you'd like us to keep producing professional free and open source software (FOSS). Consider [paying for an hour of my dev-time](https://pay.paddle.com/checkout/515568). We'll spend two hours on open source for each contribution. Yeah, that's right, you pay for one hour and get both of us to spend an hour as a thank you.
- 🚀  $99.99 — [Support for one hour or more →](https://pay.paddle.com/checkout/515568)
- 🔰  $49.99 — [Support half an hour maintenance →](https://pay.paddle.com/checkout/527253)
- ☕️  $9.99 — [Buy us lunch or coffee to keep us trucking #OpenSource →](https://pay.paddle.com/checkout/527254)

<br>

![Thanks](https://on.ahmda.ws/orkW/c)

## License & Attribution

MIT © [Ahmad Awais](https://AhmadAwais.com/).
Thanks to Composer, PHP/WordPress/WDS Coding Standards.


<br />
<br />
<p align="center">
<strong>For anything else, tweet at <a href="https://twitter.com/MrAhmadAwais/" target="_blank" rel="noopener noreferrer">@MrAhmadAwais</a></strong>
</p>

<div align="center">
	<p>I have released a video course to help you become a better developer — <a href="https://VSCode.pro/?utm_source=GitHubFOSS" target="_blank">Become a VSCode Power User →</a></p>
    <br />
  <a href="https://VSCode.pro/?utm_source=GitHubFOSS" target="_blank">
  <img src="https://raw.githubusercontent.com/ahmadawais/shades-of-purple-vscode/master/images/vscodeproPlay.jpg" /><br>VSCode</a>

  _<small><a href="https://VSCode.pro/?utm_source=GitHubFOSS" target="_blank">VSCode Power User Course →</a></small>_
</div>

