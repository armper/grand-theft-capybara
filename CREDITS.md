# Credits and third-party assets

Everything not listed here was made for this game (Blender scripts in `tools/blender/`, OpenAI images logged in `Art/generated/log.jsonl`).

| File (Art/downloads/) | What | Source | Licence | Downloaded |
|---|---|---|---|---|
| mixamo/skeleton_tpose.fbx | Skeleton only is used (the "Swat" mesh is discarded) | Adobe Mixamo, mixamo.com | Mixamo terms: free for use in games, raw files not to be redistributed | 2026-11-18, 5.7 MB |
| mixamo/idle.fbx | "Breathing Idle" animation | Adobe Mixamo | same | 2026-11-18 |
| mixamo/walk.fbx | "Walking" animation, in place | Adobe Mixamo | same | 2026-11-18 |
| mixamo/run.fbx | "Running" animation, in place | Adobe Mixamo | same | 2026-11-18 |
| mixamo/jogging.fbx | "Jogging" animation, in place, used for the regular run | Adobe Mixamo | same | 2026-11-22 |
| mixamo/female/*.fbx | "Female Basic Locomotion Pack" (idle, walking, running, jump, turns, strafes) and "Female Walk", skeleton only; Alice's idle, walk, run, sprint and jumps since 2026-11-23 | Adobe Mixamo | same | 2026-11-23, 6.6 MB |
| mixamo/fall.fbx | "Falling Idle" animation | Adobe Mixamo | same | 2026-11-18 |
| mixamo/talk.fbx | "Talking" (general conversation) animation | Adobe Mixamo | same | 2026-11-18 |

## Sketchfab models (all CC Attribution 4.0, https://creativecommons.org/licenses/by/4.0/), downloaded 2026-11-18

Each was converted for the game (scaled, re-posed, re-bound to the game's skeleton or cut out of a pack; Alice's hair recoloured).

| File (Art/downloads/sketchfab/) | Title | Author | Used for | Source |
|---|---|---|---|---|
| low-poly_woman_casual_3.glb | Low-poly Woman Casual 3 | Razvan Savescu | Alice (the player) | https://sketchfab.com/3d-models/b71bf9a6065c4836b291258f1d8587b9 |
| low-poly_woman_casual_2.glb | Low-poly Woman Casual 2 | Razvan Savescu | Former Rosa and Lola models | https://sketchfab.com/3d-models/7b127f7a90e645eca0a3a48f056fc928 |
| low-poly_man_casual_clothes_5.glb | Low-poly Man Casual Clothes 5 | Razvan Savescu | Former Tito model | https://sketchfab.com/3d-models/2cb8c4b198e64a92b4bc9d32a0f2973d |
| low-poly_man_casual_clothes_2.glb | Low-poly Man Casual Clothes 2 | Razvan Savescu | Former Marco and parking warden models | https://sketchfab.com/3d-models/4a834adf1e33405c979e94555e7955c6 |
| low-poly_man.glb | Low-poly Man | Razvan Savescu | Former Beto and pedestrian models | https://sketchfab.com/3d-models/7b93db2d46d847f191cf5e841b322856 |
| casual_npc_woman__free_low-poly_3d_model.glb | Casual NPC Woman, Free Low-Poly 3D Model | Stan (@Stas_SayHallo) | Former pedestrian model | https://sketchfab.com/3d-models/48902da4e3f8494b80e349a3cb819385 |
| old_scooter.glb | Old Scooter | Nadia Ribitis (@ribitis) | Former scooter model | https://sketchfab.com/3d-models/5e9b5072b2224ba982366490ad5f31d9 |
| capybara_ps1_style.glb | Capybara PS1 style | Kabuum | Former Don Capy and zoo animal model | https://sketchfab.com/3d-models/c5b78771af6a4099a7beb6dcbc120b07 |
| generic_passenger_car_pack.glb | Generic passenger car pack | Comrade1280 | Former parked and traffic car pack | https://sketchfab.com/3d-models/20f9af9b8a404d5cb022ac6fe87f21f5 |
| beautiful_model_with_hot_pant_and_jacket.glb | beautiful model with hot pant and jacket | kravindra191 | Alice (the player) 2026-11-18 to 2026-11-22 (no longer used in the game), at the user's request; hair recoloured blonde. Licence: Sketchfab Free Standard (not Creative Commons: use in the game is allowed, the model file itself must not be redistributed) | https://sketchfab.com/3d-models/203628e45f624ef1bc3977ad96292315 |
| low-poly_girl.glb, low-poly_woman.glb | Low-poly Girl, Low-poly Woman | Razvan Savescu | downloaded, not used (untextured) | https://sketchfab.com/razvansavescu |

Also in the project from the Unreal Engine templates (Epic Games, Unreal Engine EULA): the mannequin skeleton and its animations in `Content/Characters`.

## Our own models made with Tripo Studio

| File | Made from | Used as |
|---|---|---|
| Art/concept/alice_tpose.png | Generated with tools/genimg.py (OpenAI image model) from our own text description | Concept for Alice |
| Art/downloads/tripo/alice_tripo_hd.glb | Tripo Studio image-to-3D from the concept, on the user's account (2026-11-22), 1.93M triangles | Kept as the high-detail source |
| Art/downloads/tripo/alice_tripo_rigged.glb | The same model retopologised in Tripo to 13,777 triangles, 2k textures, auto-rigged on the Mixamo skeleton | Alice (the player), from 2026-11-22 |
| Art/concept/don_capy.png, Art/downloads/tripo/don_capy.glb | Concept from tools/genimg.py, then Tripo image-to-3D and retopology to 4,694 triangles (2026-11-22) | Don Capy |
| Art/concept/scooter.png, Art/downloads/tripo/scooter.glb | Concept from tools/genimg.py, then Tripo image-to-3D and retopology to 5,862 triangles (2026-11-22) | The scooters (replaces the Sketchfab old_scooter) |
| Art/downloads/tripo/rosa_tripo_rigged.glb, lola_tripo_rigged.glb | Original Tripo concepts, 9,417 and 9,355 triangles, Mixamo preset, 2K textures | Rosa and Lola |
| Art/downloads/tripo/marco_tripo_rigged.glb, warden_tripo_rigged.glb, tito_tripo_rigged.glb, beto_tripo_rigged.glb | Original Tripo concepts, 8,923–9,166 triangles, Mixamo preset, 2K textures | Marco, parking warden, Tito, Beto |

Original pedestrian meshes are built and skinned by the Blender character tools. The six original car bodies, adult and baby zoo capybaras, and updated zoo, market and marina props come from `tools/blender/props.py`. Storefront meshes come from `tools/blender/buildings.py`.
| Art/concept/gus_pelican.png, Art/downloads/tripo/gus_pelican.glb | Concept from tools/genimg.py, Tripo image-to-3D and retopology (2026-11-23) | Gus the pelican, case 2 |
| Art/concept/zoo_flamingo.png, zoo_goat.png, zoo_tortoise.png and the matching GLBs in Art/downloads/tripo | Concepts from tools/genimg.py, Tripo image-to-3D and retopology (2026-11-23) | Zoo pen animals |
| Art/downloads/tripo/bld_hotel_deco_a.glb | Tripo image-to-3D pilot of a building exterior (2026-11-23) | Not used in the game (looked worse than the generated building) |
| Art/concept/furn_*.png and Art/downloads/tripo/furn_*.glb (10 pieces) | Concepts from tools/genimg.py, Tripo image-to-3D and retopology (2026-11-23) | Interior furniture (replaces the home-made pieces) |
| Art/concepts/bandshell/*.png and Art/downloads/tripo/bandshell.glb | Concepts from tools/genimg.py (four, A chosen), Tripo image-to-3D and retopology (2026-11-23) | MiMo beach bandshell landmark |
| Art/concepts/street/*.png and Art/downloads/tripo/street_*.glb | Concepts from tools/genimg.py, Tripo image-to-3D and retopology (2026-11-23) | Park fountain and capybara statue, pavement fruit stand, ice-cream cart and newsstand |
| Art/concepts/street/palm.png, street_lamp.png, bench.png, bus_stop.png, planter.png and Art/downloads/tripo/street_palm/lamp/bench/bus_stop/planter.glb | Concepts from tools/genimg.py, Tripo image-to-3D (2026-11-23), reduced and baked in Blender | Palms (all five kinds), street lamps, benches, bus stops, planters |
| Art/downloads/polypizza/scarlet_macaw.glb | "Scarlet macaw" by Poly by Google, https://poly.pizza/m/7sfRRUS5F_v, CC-BY 3.0 (downloaded 2026-11-23) | Paco the parrot in case 3 |
| Art/downloads/polypizza/shiba_inu.glb | "Shiba Inu" by Quaternius, https://poly.pizza/m/y4wdQpg767, CC0 (downloaded 2026-11-24) | The dog to adopt, and the runaway dog |
| Art/downloads/polypizza/cat.glb | "Cat" by Quaternius, https://poly.pizza/m/qKICY6xla2, CC0 (downloaded 2026-11-24) | The cat to adopt |
| Art/downloads/polypizza/pigeon.glb | "Pigeon" by Quaternius, https://poly.pizza/m/9NGlBTpDEr, CC0 (downloaded 2026-11-24) | Pigeons in the squares |
| Art/downloads/polypizza/seagull.glb | "Seagull" by Poly by Google, https://poly.pizza/m/0WRzrtCIIRp, CC-BY 3.0 (downloaded 2026-11-24) | Seagulls on the beach |
| Art/downloads/pc/chrono_wedge/ | "Chrono-Wedge", made for this game by the user's own 3D model pipeline on their PC (2026-11-24): concept image by OpenAI image generation, versions 1 and 2: mesh and textures by Hunyuan3D-2.1 (Tencent Hunyuan 3D 2.1 Community License: excludes the EU, UK and South Korea, commercial-scale limits), parts by P3-SAM (Hunyuan3D-Part); from version 3.1 (the one in the game): shape by Pixal3D (TencentARC, built on Microsoft TRELLIS.2; both MIT for code and weights, checked 2026-11-24, no limits on outputs stated), texture by projecting the concept drawings; rig and export in Blender. The design is a real DeLorean as a film time machine: the user chose to keep that look (2026-11-24, a hobby game, not for sale) and to publish with it | The rare hover car |
| Art/downloads/pc/lighthouse/, clock_tower/, ferris_wheel/ | Town landmarks made for this game by the user's own 3D model pipeline on their PC (2026-11-24): concept images by OpenAI image generation, models built by hand in Blender from the picked concepts (no generated mesh, no textures) | The user's own work |
| Art/downloads/tripo/city_bus.glb | "blue city bus 3d model" by sungwi777, Tripo Studio gallery (studio.tripo3d.ai), exported 2026-11-24 for 5 credits. Tripo's terms (read 2026-11-24, https://www.tripo3d.ai/terms): free-plan makers' outputs are public and free to use and distribute (5.2.1); a paid-plan maker's public model is for personal, non-commercial use and redistribution is not spelt out (5.2.3). This maker's plan is not known | A bus standing at about one bus stop in three |
| Art/downloads/tripo/lifeguard_jetski.glb | "lifeguard jet ski 3d model" by lucas12mariano, Tripo Studio gallery, exported 2026-11-24 for 5 credits. Terms as above | Beside each lifeguard tower |
| Art/downloads/tripo/floral_capybara.glb | "floral capybara 3d model" by cheekydevsam (shown as a Pro, so paid-plan, maker: the personal, non-commercial clause applies and public redistribution is a grey area), Tripo Studio gallery, exported 2026-11-24 for 5 credits | Beside the flower stall in each park |
| Art/downloads/pc/icecream_van/, town_bus/, beach_bar/, hotdog_cart/, pier_gate/, swan_boat/, speedboat/, beach_taxi/, convertible/ | Made for this game by the user's own 3D model pipeline on their PC (2026-11-24): concept images by OpenAI image generation, models built by hand in Blender (no generated mesh, no textures) | The user's own work |
| Art/downloads/pc/ (interior_dressing, furniture_2, pier_games, play_interiors, job_props, fight_props; the one-off and walk-in buildings from cinema to alice_flat; the toy enemies clatter_crab, tin_gull, chatter_teeth, windup_robot, big_bongo) | Made for this game by the user's own 3D model pipeline on their PC (2026-11-24/25): concept images by OpenAI image generation where there was a concept round, models built by hand in Blender (no generated mesh, no textures) | The user's own work |
| Art/generated/tex2/out/int_*.png | Wallpaper and floor patterns drawn by tools/make_interior_textures.py (Pillow) | Our own |

