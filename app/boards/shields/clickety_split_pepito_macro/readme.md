Pepito-Macro

build:
    west build -d build/pepito-macro -p -b seeeduino_xiao_ble  -- -DSHIELD=clickety_split_pepito_macro

    west build -d build/pepito-macro -p -b seeeduino_xiao_ble  -- -DSHIELD="clickety_split_pepito_macro nice_view_adapter nice_view"