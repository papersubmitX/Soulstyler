
prompt_list = [
    {'style':"cloud", 'seed':0},
    {'style':"white wool", 'seed':2},
    {'style':"a sketch with crayon", 'seed':3},
    {'style':"oil painting of flowers", 'seed':7},
    {'style':'pop art of night city', 'seed':6},
    {'style':"Starry Night by Vincent van gogh", 'seed':0},
    {'style':"neon light", 'seed':5},
    {'style':"mosaic", 'seed':4},
    {'style':"green crystal", 'seed':1},
    {'style':"Underwater", 'seed':0},
    {'style':"fire", 'seed':0},
    {'style':'a graffiti style painting', 'seed':2},
    {'style':'The great wave off kanagawa by Hokusai', 'seed':0},
    {'style':'Wheatfield by Vincent van gogh', 'seed':2},
    {'style':'a Photo of white cloud', 'seed':3},
    {'style':'golden', 'seed':2},
    {'style':'Van gogh', 'seed':0},
    {'style':'pop art', 'seed':2},
    {'style':'a monet style underwater', 'seed':3},
    {'style':'A fauvism style painting', 'seed':2}
]

input_data  = [
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/ship.jpg",
        'cris_prompt' : "A white sailboat with three blue sails floating on the sea",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/911.jpg",
        'cris_prompt' : "a plane",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/1.jpg",
        'cris_prompt' : "a flower",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/house.jpg",
        'cris_prompt' : "a house",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/people.jpg",
        'cris_prompt' : "the face",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/Napoleon.jpg",
        'cris_prompt' : "The white horse under Napoleon.",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/Napoleon.jpg",
        'cris_prompt' : "white horse",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/Napoleon.jpg",
        'cris_prompt' : "horse",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/apple.png",
        'cris_prompt' : "a red apple",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/bigship.png",
        'cris_prompt' : "White Large Luxury Cruise Ship",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/car.png",
        'cris_prompt' : "White sports car.",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/lena.png",
        'cris_prompt' : "A woman's face.",
        'style_prompts' : prompt_list
    },

    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/mountain.png",
        'cris_prompt' : "mountain peak",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/tjl.png",
        'cris_prompt' : "The White House at the Taj Mahal",
        'style_prompts' : prompt_list
    },
    {
        'mask_path' : "./mask/5.jpg",
        'img_path' : "./testimg/man.jpg",
        'cris_prompt' : "The Men's face",
        'style_prompts' : prompt_list
    },

]


# 0-21 Style
cd soulstyler_org/
conda activate soulstyler

# ship finish
# CUDA_VISIBLE_DEVICES=0 python demo.py --case=0 --style=0,7

# plane
# CUDA_VISIBLE_DEVICES=3 python demo.py --case=1 --style=0,4

# flower
# CUDA_VISIBLE_DEVICES=5 python demo.py --case=2 --style=0,7

