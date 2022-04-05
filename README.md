# Electric Blue

Home Assistant theme - A dark, electric blue theme.

## Prerequisite

Check if **configuration.yaml** allows themes loading from themes folder:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

And if the **themes** folder exists in **config** folder.

Create when none exist.

### HACS installation

1. Open the Community Store (HACS).
2. Go to Frontend, open menu and select Custom Repositories.
3. Paste "https://github.com/moosedookie/Electric-Blue" in Repository field. Select Theme as Category. Then Click Add.
4. Now install.
5. Restart Home Assistant.

### Manual installation

1. Copy the file `electricblue.yaml` from the folder themes of this Git into your Home Assistant themes folder.
2. If you want the background too, copy it in `www`.
3. Restart Home Assistant.

### Enable the Background

You can use **any** background image.
To enable the background:

1. In your lovelace, click on `Configure UI > Raw configuration editor`.
2. Add the code below at the very beginning of the page.

```yaml
background: var(--background-image)
```

### Video Background

If you want something more than a static background image you can use the following:
"https://github.com/moosedookie/lovelace-animated-background".

### Enable the theme

- Open your **Profile** in Home Assistant and select the theme called **electricblue**.
