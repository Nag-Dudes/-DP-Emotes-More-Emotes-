# More-DP-Emotes
This is a simple addition to the [dpemotes](https://forum.cfx.re/t/dpemotes-1-7-390-emotes-walkingstyles-keybinding-dances-expressions-and-shared-emotes/843105) script including prop emotes only. There is a total of 9 additions which you may not want them all, so I listed the code individually to be inserted manually. However, you can also download the **AnimationList.lua** file and replace it with your file.

**Additions:**

* Carry Battery
* Carry Tire
* Food Tray
* Pizza Box
* Shopping Cart
* Show ID
* Box Trolly
* Takeout Food
* Trash Bag

[Preview Emotes](https://imgur.com/a/tkdzmp0)

**Code:**

```
   ["carrybattery"] = {"anim@heists@box_carry@", "idle", "Carry Battery", AnimationOptions =
   {
       Prop = "prop_car_battery_01",
       PropBone = 60309,
       PropPlacement = {0.025, -0.08, 0.250, -130.0, 100.0, 0.0},
       EmoteLoop = true,
       EmoteMoving = true,
   }},
   ["carrytire"] = {"anim@heists@box_carry@", "idle", "Carry Tire", AnimationOptions =
   {
       Prop = "prop_wheel_03",
       PropBone = 60309,
       PropPlacement = {0.100, 0.18, 0.250, -220.0, 480.0, 0.0},
       EmoteLoop = true,
       EmoteMoving = true,
   }},
   ["foodtray"] = {"anim@heists@box_carry@", "idle", "Food Tray", AnimationOptions =
   {
       Prop = "prop_food_tray_02",
       PropBone = 60309,
       PropPlacement = {0.225, 0.07, 0.165, -55.0, 290.0, 0.0},
       EmoteLoop = true,
       EmoteMoving = true,
   }},
   ["pizzabox"] = {"anim@heists@box_carry@", "idle", "Pizza Box", AnimationOptions =
   {
       Prop = "prop_pizza_box_02",
       PropBone = 60309,
       PropPlacement = {0.225, 0.07, 0.165, -55.0, 290.0, 0.0},
       EmoteLoop = true,
       EmoteMoving = true,
   }},
   ["shoppingcart"] = {"anim@heists@box_carry@", "idle", "Shopping Cart", AnimationOptions =
   {
       Prop = "prop_rub_trolley01a",
       PropBone = 60309,
       PropPlacement = {0.825, -0.07, -0.035, 235.0, 110.0, 0.0},
       EmoteLoop = true,
       EmoteMoving = true,
   }},
   ["showid"] = {"anim@heists@humane_labs@finale@keycards", "ped_a_enter_loop", "Show ID", AnimationOptions =
   {
       Prop = "prop_cs_swipe_card",
       PropBone = 18905,
       PropPlacement = {0.15, 0.05, 0.08, -80.0, 100.0, -20.0},
       EmoteLoop = true,
       EmoteMoving = true,
   }},
   ["trolly"] = {"anim@heists@box_carry@", "idle", "Box Trolly", AnimationOptions =
   {
       Prop = "hei_prop_hei_warehousetrolly",
       PropBone = 60309,
       PropPlacement = {1.200, -0.48, -0.115, 235.0, 110.0, 0.0},
       EmoteLoop = true,
       EmoteMoving = true,
   }},
   ["takeoutfood"] = {"anim@move_m@trash", "idle", "Takeout Food", AnimationOptions =
   {
       Prop = "prop_food_bs_bag_04",
       PropBone = 60309,
       PropPlacement = {0.355, 0.48, 0.600, -160.0, 440.0, 0.0},
       EmoteLoop = true,
       EmoteMoving = true,
   }},
   ["trashbag"] = {"anim@move_m@trash", "idle", "Trash Bag", AnimationOptions =
   {
       Prop = "prop_ld_rub_binbag_01",
       PropBone = 60309,
       PropPlacement = {0.355, 0.38, 0.600, -160.0, 440.0, 0.0},
       EmoteLoop = true,
       EmoteMoving = true,
   }},
```

**Installation:**

Open [dpemotes-master]
           ↳ Open [Client]
                         ↳ Replace **AnimationList.lua** with one from the **Download**
**OR**
Open [dpemotes-master]
           ↳ Open [Client]
                         ↳ Open [AnimationList.lua]
                                       ↳ Go to line **1652** DP.PropEmotes = {
                                                            ↳ Copy Paste Desired Emotes

**Notes:**

* If there are any issues with the emotes above I am willing to support these additions and fix any bugs that are encountered
* If you are requesting an emote (prop only) I can try my best to implement them, however, I am not capable of everything, but I'm willing to try.
* Join my discord here [Discord](https://invite.gg/dischat)
