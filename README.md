go to \extensions\stable-diffusion-webui-wd14-tagger\tagger and repalce utils.py, this adds the v3 vit tagger to the list and it will auto download from smilingwolf repo as usual.

all I did was add this to the list:

'wd14-vit.v3': WaifuDiffusionInterrogator(
        'WD14 ViT v3',
        repo_id='SmilingWolf/wd-vit-tagger-v3'
    ),


