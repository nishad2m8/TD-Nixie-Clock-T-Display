SET(SOURCES screens/ui_Screen1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c
    images/ui_img_numbers_0_png.c
    images/ui_img_numbers_1_png.c
    images/ui_img_numbers_2_png.c
    images/ui_img_numbers_3_png.c
    images/ui_img_numbers_4_png.c
    images/ui_img_numbers_5_png.c
    images/ui_img_numbers_6_png.c
    images/ui_img_numbers_7_png.c
    images/ui_img_numbers_8_png.c
    images/ui_img_numbers_9_png.c
    images/ui_img_nixie_bg_png.c)

add_library(ui ${SOURCES})
