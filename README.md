# Silhouettes

Testing sketch simplification on artistic paintings (using default model `"model_gan.t7"`)

The sketch simplification ConvNet is at ![https://github.com/bobbens/sketch_simplification](https://github.com/bobbens/sketch_simplification). The interest of the current project is to test it on artistic paintings (mainly etudes by painters, etc., see below), and not only on images similar to Japanese animes, ie., extending it to other artistic paintings.

Note: If you do not possess a CUDA GPU (or it doesn't have enough memory), it is possible to run this ConvNet on the CPU.

![Van_Gogh_Cafe_Terrace_at_Night_1888_result.jpg](extras/Van_Gogh_Cafe_Terrace_at_Night_1888_result.jpg)

![Van_Gogh_Starry_Night_Drawing_result.jpg](extras/Van_Gogh_Starry_Night_Drawing_result.jpg)

![Van_Gogh_Fishing_Boats_at_Saintes-Maries-de-la-Mer_result.jpg](extras/Van_Gogh_Fishing_Boats_at_Saintes-Maries-de-la-Mer_result.jpg)

![Van_Gogh_Street_in_Saintes-Maries-de-la-Mer_MET_70U20CH2R1_result.jpg](extras/Van_Gogh_Street_in_Saintes-Maries-de-la-Mer_MET_70U20CH2R1_result.jpg)

![Van_Gogh_Portrait_of_the_Postman_Joseph_Roulin_result.jpg](extras/Van_Gogh_Portrait_of_the_Postman_Joseph_Roulin_result.jpg)

![Leonardo_da_Vinci_Female_Head_result.jpg](extras/Leonardo_da_Vinci_Female_Head_result.jpg)

![Leonardo_da_Vinci_Head_of_a_girl_01_result.jpg](extras/Leonardo_da_Vinci_Head_of_a_girl_01_result.jpg)

![Leonardo_da_Vinci_Study_for_Madonna_with_the_Yarnwinder_result.jpg](extras/Leonardo_da_Vinci_Study_for_Madonna_with_the_Yarnwinder_result.jpg)

![Raphael_Portrait_of_a_Woman_WGA18948_result.jpg](extras/Raphael_Portrait_of_a_Woman_WGA18948_result.jpg)

![Lucas_Cranach_the_Elder_Margaret_of_Pomerania_result.jpg](extras/Lucas_Cranach_the_Elder_Margaret_of_Pomerania_result.jpg)

![Francois_Fleury_Richard_Etude_d_apres_la_Joconde_result.jpg](extras/Francois_Fleury_Richard_Etude_d_apres_la_Joconde_result.jpg)

![Renoir_The_Dance_in_the_Countryside_result.jpg](extras/Renoir_The_Dance_in_the_Countryside_result.jpg)

![Renoir_Study_for_Dance_in_the_Country_pencil_1883_542px_result.jpg](extras/Renoir_Study_for_Dance_in_the_Country_pencil_1883_542px_result.jpg)

![Degas_Study_for_a_dancer_with_arms_raised_chalk_result.jpg](extras/Degas_Study_for_a_dancer_with_arms_raised_chalk_result.jpg)

![Monet_The_Luncheon_on_the_Grass_result.jpg](extras/Monet_The_Luncheon_on_the_Grass_result.jpg)

![Paul_Cesar_Helleu_XXXI_Etude_d_apres_la_meme_result.jpg](extras/Paul_Cesar_Helleu_XXXI_Etude_d_apres_la_meme_result.jpg)

![No_61722_Chapeau_en_velours_noir_garni_de_taffetas_Winter_1911_1912_result.jpg](extras/No_61722_Chapeau_en_velours_noir_garni_de_taffetas_Winter_1911_1912_result.jpg)

![1024px-Bonnie_Bonnie_Lassie_-_newspaper_ad_-_April_1920_result.jpg](extras/1024px-Bonnie_Bonnie_Lassie_-_newspaper_ad_-_April_1920_result.jpg)

![753px-Shoes_1916_poster_result.jpg](extras/753px-Shoes_1916_poster_result.jpg)

# Citation for original work:

A test from a section of a video (original source is at ![https://en.wikipedia.org/wiki/File:London's_Royal_Ballet_I_Portrait_of_a_Dancer_Lauren_Cuthbertson.webm](https://en.wikipedia.org/wiki/File:London's_Royal_Ballet_I_Portrait_of_a_Dancer_Lauren_Cuthbertson.webm)). The result is (click below):

![video.mp4](extras/video.mp4)

# Citation for original work:

The citation for the sketch simplification at ![https://github.com/bobbens/sketch_simplification](https://github.com/bobbens/sketch_simplification) is:

      @Article{SimoSerraSIGGRAPH2016,
         author    = {Edgar Simo-Serra and Satoshi Iizuka and Kazuma Sasaki and Hiroshi Ishikawa},
         title     = {{Learning to Simplify: Fully Convolutional Networks for Rough Sketch Cleanup}},
         journal   = "ACM Transactions on Graphics (SIGGRAPH)",
         year      = 2016,
         volume    = 35,
         number    = 4,
      }

and

      @Article{SimoSerraTOG2018,
         author    = {Edgar Simo-Serra and Satoshi Iizuka and Hiroshi Ishikawa},
         title     = {{Mastering Sketching: Adversarial Augmentation for Structured Prediction}},
         journal   = "ACM Transactions on Graphics (TOG)",
         year      = 2018,
         volume    = 37,
         number    = 1,
      }

