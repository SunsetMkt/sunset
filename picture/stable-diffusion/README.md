# Stable Diffusion

## Suggested Models

[Anything XL](https://civitai.com/models/9409/anything-v5-or-anything-diffusion-original)

[Blue Archive Flat Celluloid Style Fine-tune](https://civitai.com/models/212253/baxl-or-blue-archive-flat-celluloid-style-fine-tune-or-kohaku-d-and-animagine-xl-v3)

## Prompts

### For avatars

Positive: `masterpiece,best quality,1girl,portrait,upper body,day,available light,background light,colorful,simple background,looking at viewer,solo,small breasts,ahoge,bangs,medium hair,closed mouth,black eyes,glasses,black-framed eyewear,labcoat,black shirt,expressionless,blonde hair,professional,light smile,`

Negative: `nsfw,lowres,bad anatomy,bad hands,text,error,missing fingers,extra digit,fewer digits,cropped,worst quality,low quality,normal quality,jpeg artifacts,signature,watermark,username,blurry,artist name,`

`Steps: 20, Sampler: DPM++ 2M, Schedule type: Karras, CFG scale: 7, Size: 1024x1024`

#### For Blue Archive Flat Celluloid Style Fine-tune

_Always no light on face, don't know why._

Positive: `masterpiece,best quality,1girl,portrait,upper body,day,bright face,Cinematic Lighting,available light,background light,white background,simple background,looking at viewer,solo,small breasts,ahoge,bangs,medium hair,closed mouth,black eyes,glasses,black-framed eyewear,labcoat,black shirt,expressionless,blonde hair,professional,light smile,`

Negative: `nsfw,lowres,error,worst quality,low quality,jpeg artifacts,signature,username,blurry,chibi,text,backlighting,`

_Better._

```plaintext
1girl,solo,portrait,(bright:1.5),(white background:1.5),(soft lighting:1.3),(light on face:1.1),labcoat,black shirt,glasses,simple background,looking at viewer,small breasts,ahoge,bangs,medium hair,closed mouth,black eyes,blonde hair,black-framed eyewear,light smile,masterpiece,best quality,highres,absurdres,
Negative prompt: (shaded face:1.5),(shadow:1.3),(backlighting:1.2),(dark:1.1),nsfw,lowres,error,worst quality,low quality,jpeg artifacts,signature,username,blurry,chibi,text,
```

_Mobile Wallpaper_

```plaintext
1girl,original,full_shot,solo,labcoat,black shirt,glasses,hand_in_pocket,looking at viewer,small breasts,(mechanical halo:1.5),halo,ahoge,bangs,medium hair,closed mouth,black eyes,blonde hair,black-framed eyewear,light smile,blue archive,city,jeans,sneakers,blue archive sky,best quality,masterpiece,highres,absurdres,
Negative prompt: nsfw,lowres,error,worst quality,low quality,jpeg artifacts,signature,username,blurry,chibi,text,
Steps: 20, Sampler: DPM++ 2M, Schedule type: Karras, CFG scale: 7, Seed: 2908748399, Size: 864x1920, Model hash: 95affd8c8f, Model: baxlBlueArchiveFlatCelluloidStyleFineTune_xlv3, Clip skip: 2, Version: v1.9.3
```
