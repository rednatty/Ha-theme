<h3 align="center">
	redNatty theme for <a href="https://www.home-assistant.io/">Home Assistant</a>

</h3>

<p align="center">
	<a href="https://github.com/rednatty/rednatty-theme/stargazers"><img src="https://img.shields.io/github/stars/rednatty/rednatty-theme?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/rednatty/rednatty-theme/issues"><img src="https://img.shields.io/github/issues/rednatty/rednatty-theme?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/rednatty/rednatty-theme/contributors"><img src="https://img.shields.io/github/contributors/rednatty/rednatty-theme?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

## Images:
<details>
    <img src="https://raw.githubusercontent.com/rednatty/rednatty-theme/main/assets/images/Overview.webp"/>
    <img src="https://raw.githubusercontent.com/rednatty/rednatty-theme/main/assets/images/Map.webp"/>
    <img src="https://raw.githubusercontent.com/rednatty/rednatty-theme/main/assets/images/Logbook.webp"/>
    <img src="https://raw.githubusercontent.com/rednatty/rednatty-theme/main/assets/images/History.webp"/>
    <img src="https://raw.githubusercontent.com/rednatty/rednatty-theme/main/assets/images/Code.webp"/>
    <img src="https://raw.githubusercontent.com/rednatty/rednatty-theme/main/assets/images/Devtools.webp"/>
    <img src="https://raw.githubusercontent.com/rednatty/rednatty-theme/main/assets/images/Settings.webp"/>
    <img src="https://raw.githubusercontent.com/rednatty/rednatty-theme/main/assets/images/Profile.webp"/>

</details>

## Usage
### With [HACS](https://hacs.xyz/)
1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```
2. Go to the Community Store.
3. Search for `redNatty`.
4. Navigate to `redNatty` theme.
5. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.

### Manual
1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```
2. Clone the repository
```bash
git clone https://github.com/rednatty/rednatty-theme.git
```

3. Copy `themes/rednatty.yaml` in your existing (or create it) `themes/` folder.

```bash
mv home-assistant/themes/rednatty.yaml ~/config/themes/.
```
