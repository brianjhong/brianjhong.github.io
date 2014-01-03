---
toolbar: false
size: lg  #leave empty for default, otherwise lg, sm, xs
vertical: false
justified: false
left: default left button
center: default center button
right: default right button
---

<div class="btn-group{{# this_config.size}}-{{this_config.size}}{{/ this_config.size}} {{# this_config.vertical}}btn-group-vertical{{/ this_config.vertical}} {{# this_config.justified }}btn-group-justified{{/ this_config.justified}}" {{# this_config.toolbar }}role="toolbar"{{/ this_config.toolbar }}>
    {{# this_config.left }}<button type="button" class="btn btn-default">{{ this_config.left }}</button>{{/ this_config.left }}
    {{# this_config.center }}<button type="button" class="btn btn-default">{{ this_config.center }}</button>{{/ this_config.center }}
    {{# this_config.right }}<button type="button" class="btn btn-default">{{ this_config.right }}</button>{{/ this_config.right }}
</div>