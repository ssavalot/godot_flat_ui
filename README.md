The repository contain a flat design for Godot engine.

Download and copy the files into your godot source folders and change the following files.

tools/editor/editor_node.cpp

theme->set_color("prop_category","Editor",Color::hex(0x3f3a44ff));
theme->set_color("prop_section","Editor",Color::hex(0x35313aff));
theme->set_color("prop_subsection","Editor",Color::hex(0x312e37ff));

replace:

theme->set_color("prop_category","Editor",Color::hex(0x00000000));
theme->set_color("prop_section","Editor",Color::hex(0x00000000));
theme->set_color("prop_subsection","Editor",Color::hex(0x00000000));


tools/editor/animation_editor.cpp

timecolor = Color::html("ff4a414f");

replace:

timecolor = Color::html("ff275067");


Finally, build and run.

