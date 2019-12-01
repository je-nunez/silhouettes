# Silhouettes

Testing sketch simplification on artistic paintings (using default model `"model_gan.t7"`)

# WIP

This project is a *work in progress*. The implementation is *incomplete* and subject to change. The documentation can be inaccurate.

# Details of current repo:

The sketch simplification ConvNet is at Edgar Simo-Serra's site: [https://github.com/bobbens/sketch_simplification](https://github.com/bobbens/sketch_simplification) (read full citations [here](#citation-for-original-work)). The interest of the current project is to test it on artistic paintings (mainly etudes by painters, etc., see below), and not only on images similar to Japanese animes and other drawings, ie., extending it to other artistic paintings (Impressionism, Renaissance, etc).

Note: If you do not possess a CUDA GPU (or it doesn't have enough memory), it is possible to run this ConvNet on the CPU.

* Van Gogh's sketch for his "Cafe Terrace at Night":

![Van_Gogh_Cafe_Terrace_at_Night_1888_result.jpg](extras/Van_Gogh_Cafe_Terrace_at_Night_1888_result.jpg)

* Van Gogh's drawing for "The Starry Night":

![Van_Gogh_Starry_Night_Drawing_result.jpg](extras/Van_Gogh_Starry_Night_Drawing_result.jpg)

* Van Gogh's drawing for "The Fishing Boats at Saintes-Maries-de-la-Mer":

![Van_Gogh_Fishing_Boats_at_Saintes-Maries-de-la-Mer_result.jpg](extras/Van_Gogh_Fishing_Boats_at_Saintes-Maries-de-la-Mer_result.jpg)

* Van Gogh's drawing for "The Street in Saintes-Maries-de-la-Mer":

![Van_Gogh_Street_in_Saintes-Maries-de-la-Mer_MET_70U20CH2R1_result.jpg](extras/Van_Gogh_Street_in_Saintes-Maries-de-la-Mer_MET_70U20CH2R1_result.jpg)

* Van Gogh's drawing for the "Portrait of the Postman Joseph Roulin":

![Van_Gogh_Portrait_of_the_Postman_Joseph_Roulin_result.jpg](extras/Van_Gogh_Portrait_of_the_Postman_Joseph_Roulin_result.jpg)

* Leonardo da Vinci's drawing for a "Female Head":

![Leonardo_da_Vinci_Female_Head_result.jpg](extras/Leonardo_da_Vinci_Female_Head_result.jpg)

* Leonardo da Vinci's drawing for "Head of a girl":

![Leonardo_da_Vinci_Head_of_a_girl_01_result.jpg](extras/Leonardo_da_Vinci_Head_of_a_girl_01_result.jpg)

* Leonardo da Vinci's study for "Madonna with the Yarnwinder":

![Leonardo_da_Vinci_Study_for_Madonna_with_the_Yarnwinder_result.jpg](extras/Leonardo_da_Vinci_Study_for_Madonna_with_the_Yarnwinder_result.jpg)

* Raphael's drawing for "Portrait of a Woman - WGA18948":

![Raphael_Portrait_of_a_Woman_WGA18948_result.jpg](extras/Raphael_Portrait_of_a_Woman_WGA18948_result.jpg)

* Lucas Cranach the Elder's drawing for "Margaret of Pomerania":

![Lucas_Cranach_the_Elder_Margaret_of_Pomerania_result.jpg](extras/Lucas_Cranach_the_Elder_Margaret_of_Pomerania_result.jpg)

* Francois Fleury Richard's etude d'apres "La Joconde":

![Francois_Fleury_Richard_Etude_d_apres_la_Joconde_result.jpg](extras/Francois_Fleury_Richard_Etude_d_apres_la_Joconde_result.jpg)

* Pierre-Auguste Renoir's etching for the "Dance in the Country":

![Renoir_The_Dance_in_the_Countryside_result.jpg](extras/Renoir_The_Dance_in_the_Countryside_result.jpg)

* Pierre-Auguste Renoir's drawing for the "Dance in the Country":

![Renoir_Study_for_Dance_in_the_Country_pencil_1883_542px_result.jpg](extras/Renoir_Study_for_Dance_in_the_Country_pencil_1883_542px_result.jpg)

* Edgar Degas' study for "A dancer with arms raised":

![Degas_Study_for_a_dancer_with_arms_raised_chalk_result.jpg](extras/Degas_Study_for_a_dancer_with_arms_raised_chalk_result.jpg)

* Claude Monet's study for "The Luncheon on the Grass":

![Monet_The_Luncheon_on_the_Grass_result.jpg](extras/Monet_The_Luncheon_on_the_Grass_result.jpg)

* Paul Cesar Helleu's etching for "Etude d'apres la meme" (plate XXXI):

![Paul_Cesar_Helleu_XXXI_Etude_d_apres_la_meme_result.jpg](extras/Paul_Cesar_Helleu_XXXI_Etude_d_apres_la_meme_result.jpg)

* A drawing in a magazine (No 61722 Chapeau en velours noir garni de taffetas Winter 1911 1912):

![No_61722_Chapeau_en_velours_noir_garni_de_taffetas_Winter_1911_1912_result.jpg](extras/No_61722_Chapeau_en_velours_noir_garni_de_taffetas_Winter_1911_1912_result.jpg)

* Newspaper ad for the movie "Bonnie, Bonnie Lassie" (1919):

![1024px-Bonnie_Bonnie_Lassie_-_newspaper_ad_-_April_1920_result.jpg](extras/1024px-Bonnie_Bonnie_Lassie_-_newspaper_ad_-_April_1920_result.jpg)

* Poster for the film "Shoes" (1916):

![753px-Shoes_1916_poster_result.jpg](extras/753px-Shoes_1916_poster_result.jpg)

# A test with a video

A test from a section of a video (the original source is at [https://en.wikipedia.org/wiki/File:London's_Royal_Ballet_I_Portrait_of_a_Dancer_Lauren_Cuthbertson.webm](https://en.wikipedia.org/wiki/File:London's_Royal_Ballet_I_Portrait_of_a_Dancer_Lauren_Cuthbertson.webm)). The result is (click below):

![![video.mp4](extras/video_screenshot.png)](extras/video.mp4)

# Citation for original work

The citation for the sketch simplification at [https://github.com/bobbens/sketch_simplification](https://github.com/bobbens/sketch_simplification) is:

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

