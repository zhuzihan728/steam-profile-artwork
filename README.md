# Steam Profile Artwork Generator
Personal repo for creating my custom animated Steam profile artwork, bear with me if the code looks shit, it works for me and that's all I need.

## Workflow

1. **Extract anime frames**: Use [ezgif](https://ezgif.com) to convert clip to PNG/JPG frames (10 FPS) → `./frames`

2. **Remove backgrounds**: Run `script.ipynb` with [anime-segmentation](https://github.com/SkyTNT/anime-segmentation)

3. **Get Steam background**: Visit [steam.design](https://steam.design/) → inspect element → find MP4 URL

4. **Extract background frames**: Use [ezgif](https://ezgif.com) to convert background MP4 to frames (10 FPS) → `./steam_image_blend/bg`

5. **Blend images**: Run `steam_image_blend/img_paste.ipynb` to composite final artwork


## Showcase
![a](assets/example1.gif)
![a](assets/example2.gif)
