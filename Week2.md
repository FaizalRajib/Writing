<!DOCTYPE html>
<!-- saved from url=(0021)https://dillinger.io/ -->
<html lang="en" ng-strict-di=""><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><style type="text/css">@charset "UTF-8";[ng\:cloak],[ng-cloak],[data-ng-cloak],[x-ng-cloak],.ng-cloak,.x-ng-cloak,.ng-hide:not(.ng-hide-animate){display:none !important;}ng\:form{display:block;}.ng-animate-shim{visibility:hidden;}.ng-anchor{position:absolute;}</style>

<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<title>Online Markdown Editor - Dillinger, the Last Markdown Editor ever.</title>
<meta name="description" content="Dillinger is an online cloud based HTML5 filled
  Markdown Editor. Sync with Dropbox, Github, Google Drive or OneDrive.
  Convert HTML to Markdown. 100% Open Source!">
<meta name="keywords" content="Markdown, Dillinger, Editor, ACE, Github, Open Source, Node.js">
<meta name="author" content="Joe McCann and Martin Broder">
<link rel="apple-touch-icon" href="https://dillinger.io/apple-touch-icon.png">


<meta name="robots" content="noodp, noydir">

<meta name="google-site-verification" content="DAyGOgtsg8rJpq9VVktKzDkQ1UhXm1FYl8SD47hPkjA">

<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no, maximum-scale=1, minimum-scale=1">
<meta name="HandheldFriendly" content="true">
<meta name="MobileOptimized" content="320">
<meta http-equiv="cleartype" content="on">
<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,600,700" rel="stylesheet" type="text/css">
<link href="https://fonts.googleapis.com/css?family=Ubuntu+Mono:400,700,400italic,700italic" rel="stylesheet" type="text/css">
<link href="./Week2_files/app.css" rel="stylesheet">
<script type="text/javascript">
   var trackOutboundLink = function(url) {
    ga('send', 'event', 'outbound', 'click', url, {
      'transport': 'beacon',
      'hitCallback': function(){window.open(url);}
    });
    }
  </script>
<div id="_bsa_srv-CVADP53W_0"></div><style id="ace_editor.css">.ace_editor {position: relative;overflow: hidden;font: 12px/normal 'Monaco', 'Menlo', 'Ubuntu Mono', 'Consolas', 'source-code-pro', monospace;direction: ltr;text-align: left;-webkit-tap-highlight-color: rgba(0, 0, 0, 0);}.ace_scroller {position: absolute;overflow: hidden;top: 0;bottom: 0;background-color: inherit;-ms-user-select: none;-moz-user-select: none;-webkit-user-select: none;user-select: none;cursor: text;}.ace_content {position: absolute;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;min-width: 100%;}.ace_dragging .ace_scroller:before{position: absolute;top: 0;left: 0;right: 0;bottom: 0;content: '';background: rgba(250, 250, 250, 0.01);z-index: 1000;}.ace_dragging.ace_dark .ace_scroller:before{background: rgba(0, 0, 0, 0.01);}.ace_selecting, .ace_selecting * {cursor: text !important;}.ace_gutter {position: absolute;overflow : hidden;width: auto;top: 0;bottom: 0;left: 0;cursor: default;z-index: 4;-ms-user-select: none;-moz-user-select: none;-webkit-user-select: none;user-select: none;}.ace_gutter-active-line {position: absolute;left: 0;right: 0;}.ace_scroller.ace_scroll-left {box-shadow: 17px 0 16px -16px rgba(0, 0, 0, 0.4) inset;}.ace_gutter-cell {padding-left: 19px;padding-right: 6px;background-repeat: no-repeat;}.ace_gutter-cell.ace_error {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAABOFBMVEX/////////QRswFAb/Ui4wFAYwFAYwFAaWGAfDRymzOSH/PxswFAb/SiUwFAYwFAbUPRvjQiDllog5HhHdRybsTi3/Tyv9Tir+Syj/UC3////XurebMBIwFAb/RSHbPx/gUzfdwL3kzMivKBAwFAbbvbnhPx66NhowFAYwFAaZJg8wFAaxKBDZurf/RB6mMxb/SCMwFAYwFAbxQB3+RB4wFAb/Qhy4Oh+4QifbNRcwFAYwFAYwFAb/QRzdNhgwFAYwFAbav7v/Uy7oaE68MBK5LxLewr/r2NXewLswFAaxJw4wFAbkPRy2PyYwFAaxKhLm1tMwFAazPiQwFAaUGAb/QBrfOx3bvrv/VC/maE4wFAbRPBq6MRO8Qynew8Dp2tjfwb0wFAbx6eju5+by6uns4uH9/f36+vr/GkHjAAAAYnRSTlMAGt+64rnWu/bo8eAA4InH3+DwoN7j4eLi4xP99Nfg4+b+/u9B/eDs1MD1mO7+4PHg2MXa347g7vDizMLN4eG+Pv7i5evs/v79yu7S3/DV7/498Yv24eH+4ufQ3Ozu/v7+y13sRqwAAADLSURBVHjaZc/XDsFgGIBhtDrshlitmk2IrbHFqL2pvXf/+78DPokj7+Fz9qpU/9UXJIlhmPaTaQ6QPaz0mm+5gwkgovcV6GZzd5JtCQwgsxoHOvJO15kleRLAnMgHFIESUEPmawB9ngmelTtipwwfASilxOLyiV5UVUyVAfbG0cCPHig+GBkzAENHS0AstVF6bacZIOzgLmxsHbt2OecNgJC83JERmePUYq8ARGkJx6XtFsdddBQgZE2nPR6CICZhawjA4Fb/chv+399kfR+MMMDGOQAAAABJRU5ErkJggg==");background-repeat: no-repeat;background-position: 2px center;}.ace_gutter-cell.ace_warning {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAmVBMVEX///8AAAD///8AAAAAAABPSzb/5sAAAAB/blH/73z/ulkAAAAAAAD85pkAAAAAAAACAgP/vGz/rkDerGbGrV7/pkQICAf////e0IsAAAD/oED/qTvhrnUAAAD/yHD/njcAAADuv2r/nz//oTj/p064oGf/zHAAAAA9Nir/tFIAAAD/tlTiuWf/tkIAAACynXEAAAAAAAAtIRW7zBpBAAAAM3RSTlMAABR1m7RXO8Ln31Z36zT+neXe5OzooRDfn+TZ4p3h2hTf4t3k3ucyrN1K5+Xaks52Sfs9CXgrAAAAjklEQVR42o3PbQ+CIBQFYEwboPhSYgoYunIqqLn6/z8uYdH8Vmdnu9vz4WwXgN/xTPRD2+sgOcZjsge/whXZgUaYYvT8QnuJaUrjrHUQreGczuEafQCO/SJTufTbroWsPgsllVhq3wJEk2jUSzX3CUEDJC84707djRc5MTAQxoLgupWRwW6UB5fS++NV8AbOZgnsC7BpEAAAAABJRU5ErkJggg==");background-position: 2px center;}.ace_gutter-cell.ace_info {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAAAAAA6mKC9AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAAJ0Uk5TAAB2k804AAAAPklEQVQY02NgIB68QuO3tiLznjAwpKTgNyDbMegwisCHZUETUZV0ZqOquBpXj2rtnpSJT1AEnnRmL2OgGgAAIKkRQap2htgAAAAASUVORK5CYII=");background-position: 2px center;}.ace_dark .ace_gutter-cell.ace_info {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQBAMAAADt3eJSAAAAJFBMVEUAAAChoaGAgIAqKiq+vr6tra1ZWVmUlJSbm5s8PDxubm56enrdgzg3AAAAAXRSTlMAQObYZgAAAClJREFUeNpjYMAPdsMYHegyJZFQBlsUlMFVCWUYKkAZMxZAGdxlDMQBAG+TBP4B6RyJAAAAAElFTkSuQmCC");}.ace_scrollbar {position: absolute;right: 0;bottom: 0;z-index: 6;}.ace_scrollbar-inner {position: absolute;cursor: text;left: 0;top: 0;}.ace_scrollbar-v{overflow-x: hidden;overflow-y: scroll;top: 0;}.ace_scrollbar-h {overflow-x: scroll;overflow-y: hidden;left: 0;}.ace_print-margin {position: absolute;height: 100%;}.ace_text-input {position: absolute;z-index: 0;width: 0.5em;height: 1em;opacity: 0;background: transparent;-moz-appearance: none;appearance: none;border: none;resize: none;outline: none;overflow: hidden;font: inherit;padding: 0 1px;margin: 0 -1px;text-indent: -1em;-ms-user-select: text;-moz-user-select: text;-webkit-user-select: text;user-select: text;white-space: pre!important;}.ace_text-input.ace_composition {background: inherit;color: inherit;z-index: 1000;opacity: 1;text-indent: 0;}.ace_layer {z-index: 1;position: absolute;overflow: hidden;word-wrap: normal;white-space: pre;height: 100%;width: 100%;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;pointer-events: none;}.ace_gutter-layer {position: relative;width: auto;text-align: right;pointer-events: auto;}.ace_text-layer {font: inherit !important;}.ace_cjk {display: inline-block;text-align: center;}.ace_cursor-layer {z-index: 4;}.ace_cursor {z-index: 4;position: absolute;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;border-left: 2px solid;transform: translatez(0);}.ace_multiselect .ace_cursor {border-left-width: 1px;}.ace_slim-cursors .ace_cursor {border-left-width: 1px;}.ace_overwrite-cursors .ace_cursor {border-left-width: 0;border-bottom: 1px solid;}.ace_hidden-cursors .ace_cursor {opacity: 0.2;}.ace_smooth-blinking .ace_cursor {-webkit-transition: opacity 0.18s;transition: opacity 0.18s;}.ace_marker-layer .ace_step, .ace_marker-layer .ace_stack {position: absolute;z-index: 3;}.ace_marker-layer .ace_selection {position: absolute;z-index: 5;}.ace_marker-layer .ace_bracket {position: absolute;z-index: 6;}.ace_marker-layer .ace_active-line {position: absolute;z-index: 2;}.ace_marker-layer .ace_selected-word {position: absolute;z-index: 4;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;}.ace_line .ace_fold {-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;display: inline-block;height: 11px;margin-top: -2px;vertical-align: middle;background-image:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAJCAYAAADU6McMAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAJpJREFUeNpi/P//PwOlgAXGYGRklAVSokD8GmjwY1wasKljQpYACtpCFeADcHVQfQyMQAwzwAZI3wJKvCLkfKBaMSClBlR7BOQikCFGQEErIH0VqkabiGCAqwUadAzZJRxQr/0gwiXIal8zQQPnNVTgJ1TdawL0T5gBIP1MUJNhBv2HKoQHHjqNrA4WO4zY0glyNKLT2KIfIMAAQsdgGiXvgnYAAAAASUVORK5CYII="),url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAA3CAYAAADNNiA5AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAACJJREFUeNpi+P//fxgTAwPDBxDxD078RSX+YeEyDFMCIMAAI3INmXiwf2YAAAAASUVORK5CYII=");background-repeat: no-repeat, repeat-x;background-position: center center, top left;color: transparent;border: 1px solid black;border-radius: 2px;cursor: pointer;pointer-events: auto;}.ace_dark .ace_fold {}.ace_fold:hover{background-image:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAJCAYAAADU6McMAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAJpJREFUeNpi/P//PwOlgAXGYGRklAVSokD8GmjwY1wasKljQpYACtpCFeADcHVQfQyMQAwzwAZI3wJKvCLkfKBaMSClBlR7BOQikCFGQEErIH0VqkabiGCAqwUadAzZJRxQr/0gwiXIal8zQQPnNVTgJ1TdawL0T5gBIP1MUJNhBv2HKoQHHjqNrA4WO4zY0glyNKLT2KIfIMAAQsdgGiXvgnYAAAAASUVORK5CYII="),url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAA3CAYAAADNNiA5AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAACBJREFUeNpi+P//fz4TAwPDZxDxD5X4i5fLMEwJgAADAEPVDbjNw87ZAAAAAElFTkSuQmCC");}.ace_tooltip {background-color: #FFF;background-image: -webkit-linear-gradient(top, transparent, rgba(0, 0, 0, 0.1));background-image: linear-gradient(to bottom, transparent, rgba(0, 0, 0, 0.1));border: 1px solid gray;border-radius: 1px;box-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);color: black;max-width: 100%;padding: 3px 4px;position: fixed;z-index: 999999;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;cursor: default;white-space: pre;word-wrap: break-word;line-height: normal;font-style: normal;font-weight: normal;letter-spacing: normal;pointer-events: none;}.ace_folding-enabled > .ace_gutter-cell {padding-right: 13px;}.ace_fold-widget {-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;margin: 0 -12px 0 1px;display: none;width: 11px;vertical-align: top;background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAANElEQVR42mWKsQ0AMAzC8ixLlrzQjzmBiEjp0A6WwBCSPgKAXoLkqSot7nN3yMwR7pZ32NzpKkVoDBUxKAAAAABJRU5ErkJggg==");background-repeat: no-repeat;background-position: center;border-radius: 3px;border: 1px solid transparent;cursor: pointer;}.ace_folding-enabled .ace_fold-widget {display: inline-block;   }.ace_fold-widget.ace_end {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAANElEQVR42m3HwQkAMAhD0YzsRchFKI7sAikeWkrxwScEB0nh5e7KTPWimZki4tYfVbX+MNl4pyZXejUO1QAAAABJRU5ErkJggg==");}.ace_fold-widget.ace_closed {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAMAAAAGCAYAAAAG5SQMAAAAOUlEQVR42jXKwQkAMAgDwKwqKD4EwQ26sSOkVWjgIIHAzPiCgaqiqnJHZnKICBERHN194O5b9vbLuAVRL+l0YWnZAAAAAElFTkSuQmCCXA==");}.ace_fold-widget:hover {border: 1px solid rgba(0, 0, 0, 0.3);background-color: rgba(255, 255, 255, 0.2);box-shadow: 0 1px 1px rgba(255, 255, 255, 0.7);}.ace_fold-widget:active {border: 1px solid rgba(0, 0, 0, 0.4);background-color: rgba(0, 0, 0, 0.05);box-shadow: 0 1px 1px rgba(255, 255, 255, 0.8);}.ace_dark .ace_fold-widget {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHklEQVQIW2P4//8/AzoGEQ7oGCaLLAhWiSwB146BAQCSTPYocqT0AAAAAElFTkSuQmCC");}.ace_dark .ace_fold-widget.ace_end {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAH0lEQVQIW2P4//8/AxQ7wNjIAjDMgC4AxjCVKBirIAAF0kz2rlhxpAAAAABJRU5ErkJggg==");}.ace_dark .ace_fold-widget.ace_closed {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAMAAAAFCAYAAACAcVaiAAAAHElEQVQIW2P4//+/AxAzgDADlOOAznHAKgPWAwARji8UIDTfQQAAAABJRU5ErkJggg==");}.ace_dark .ace_fold-widget:hover {box-shadow: 0 1px 1px rgba(255, 255, 255, 0.2);background-color: rgba(255, 255, 255, 0.1);}.ace_dark .ace_fold-widget:active {box-shadow: 0 1px 1px rgba(255, 255, 255, 0.2);}.ace_fold-widget.ace_invalid {background-color: #FFB4B4;border-color: #DE5555;}.ace_fade-fold-widgets .ace_fold-widget {-webkit-transition: opacity 0.4s ease 0.05s;transition: opacity 0.4s ease 0.05s;opacity: 0;}.ace_fade-fold-widgets:hover .ace_fold-widget {-webkit-transition: opacity 0.05s ease 0.05s;transition: opacity 0.05s ease 0.05s;opacity:1;}.ace_underline {text-decoration: underline;}.ace_bold {font-weight: bold;}.ace_nobold .ace_bold {font-weight: normal;}.ace_italic {font-style: italic;}.ace_error-marker {background-color: rgba(255, 0, 0,0.2);position: absolute;z-index: 9;}.ace_highlight-marker {background-color: rgba(255, 255, 0,0.2);position: absolute;z-index: 8;}.ace_br1 {border-top-left-radius    : 3px;}.ace_br2 {border-top-right-radius   : 3px;}.ace_br3 {border-top-left-radius    : 3px; border-top-right-radius:    3px;}.ace_br4 {border-bottom-right-radius: 3px;}.ace_br5 {border-top-left-radius    : 3px; border-bottom-right-radius: 3px;}.ace_br6 {border-top-right-radius   : 3px; border-bottom-right-radius: 3px;}.ace_br7 {border-top-left-radius    : 3px; border-top-right-radius:    3px; border-bottom-right-radius: 3px;}.ace_br8 {border-bottom-left-radius : 3px;}.ace_br9 {border-top-left-radius    : 3px; border-bottom-left-radius:  3px;}.ace_br10{border-top-right-radius   : 3px; border-bottom-left-radius:  3px;}.ace_br11{border-top-left-radius    : 3px; border-top-right-radius:    3px; border-bottom-left-radius:  3px;}.ace_br12{border-bottom-right-radius: 3px; border-bottom-left-radius:  3px;}.ace_br13{border-top-left-radius    : 3px; border-bottom-right-radius: 3px; border-bottom-left-radius:  3px;}.ace_br14{border-top-right-radius   : 3px; border-bottom-right-radius: 3px; border-bottom-left-radius:  3px;}.ace_br15{border-top-left-radius    : 3px; border-top-right-radius:    3px; border-bottom-right-radius: 3px; border-bottom-left-radius: 3px;}.ace_text-input-ios {position: absolute !important;top: -100000px !important;left: -100000px !important;}
/*# sourceURL=ace/css/ace_editor.css */</style><style id="ace-tm">.ace-tm .ace_gutter {background: #f0f0f0;color: #333;}.ace-tm .ace_print-margin {width: 1px;background: #e8e8e8;}.ace-tm .ace_fold {background-color: #6B72E6;}.ace-tm {background-color: #FFFFFF;color: black;}.ace-tm .ace_cursor {color: black;}.ace-tm .ace_invisible {color: rgb(191, 191, 191);}.ace-tm .ace_storage,.ace-tm .ace_keyword {color: blue;}.ace-tm .ace_constant {color: rgb(197, 6, 11);}.ace-tm .ace_constant.ace_buildin {color: rgb(88, 72, 246);}.ace-tm .ace_constant.ace_language {color: rgb(88, 92, 246);}.ace-tm .ace_constant.ace_library {color: rgb(6, 150, 14);}.ace-tm .ace_invalid {background-color: rgba(255, 0, 0, 0.1);color: red;}.ace-tm .ace_support.ace_function {color: rgb(60, 76, 114);}.ace-tm .ace_support.ace_constant {color: rgb(6, 150, 14);}.ace-tm .ace_support.ace_type,.ace-tm .ace_support.ace_class {color: rgb(109, 121, 222);}.ace-tm .ace_keyword.ace_operator {color: rgb(104, 118, 135);}.ace-tm .ace_string {color: rgb(3, 106, 7);}.ace-tm .ace_comment {color: rgb(76, 136, 107);}.ace-tm .ace_comment.ace_doc {color: rgb(0, 102, 255);}.ace-tm .ace_comment.ace_doc.ace_tag {color: rgb(128, 159, 191);}.ace-tm .ace_constant.ace_numeric {color: rgb(0, 0, 205);}.ace-tm .ace_variable {color: rgb(49, 132, 149);}.ace-tm .ace_xml-pe {color: rgb(104, 104, 91);}.ace-tm .ace_entity.ace_name.ace_function {color: #0000A2;}.ace-tm .ace_heading {color: rgb(12, 7, 255);}.ace-tm .ace_list {color:rgb(185, 6, 144);}.ace-tm .ace_meta.ace_tag {color:rgb(0, 22, 142);}.ace-tm .ace_string.ace_regex {color: rgb(255, 0, 0)}.ace-tm .ace_marker-layer .ace_selection {background: rgb(181, 213, 255);}.ace-tm.ace_multiselect .ace_selection.ace_start {box-shadow: 0 0 3px 0px white;}.ace-tm .ace_marker-layer .ace_step {background: rgb(252, 255, 0);}.ace-tm .ace_marker-layer .ace_stack {background: rgb(164, 229, 101);}.ace-tm .ace_marker-layer .ace_bracket {margin: -1px 0 0 -1px;border: 1px solid rgb(192, 192, 192);}.ace-tm .ace_marker-layer .ace_active-line {background: rgba(0, 0, 0, 0.07);}.ace-tm .ace_gutter-active-line {background-color : #dcdcdc;}.ace-tm .ace_marker-layer .ace_selected-word {background: rgb(250, 250, 255);border: 1px solid rgb(200, 200, 250);}.ace-tm .ace_indent-guide {background: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAACCAYAAACZgbYnAAAAE0lEQVQImWP4////f4bLly//BwAmVgd1/w11/gAAAABJRU5ErkJggg==") right repeat-y;}
/*# sourceURL=ace/css/ace-tm */</style><style>    .error_widget_wrapper {        background: inherit;        color: inherit;        border:none    }    .error_widget {        border-top: solid 2px;        border-bottom: solid 2px;        margin: 5px 0;        padding: 10px 40px;        white-space: pre-wrap;    }    .error_widget.ace_error, .error_widget_arrow.ace_error{        border-color: #ff5a5a    }    .error_widget.ace_warning, .error_widget_arrow.ace_warning{        border-color: #F1D817    }    .error_widget.ace_info, .error_widget_arrow.ace_info{        border-color: #5a5a5a    }    .error_widget.ace_ok, .error_widget_arrow.ace_ok{        border-color: #5aaa5a    }    .error_widget_arrow {        position: absolute;        border: solid 5px;        border-top-color: transparent!important;        border-right-color: transparent!important;        border-left-color: transparent!important;        top: -5px;    }</style><script src="./Week2_files/theme-github.js.download"></script></head>
<body ng-controller="Base" file-import-drop-target="" class="ng-scope" style="overflow: hidden;">
<input type="file" accept=".md,.markdown,text/html" file-import-choose-file="" style="display: none;">
<form method="POST" id="downloader" class="ng-pristine ng-valid">
<input type="hidden" name="name" autocomplete="off">
<input type="hidden" name="unmd" autocomplete="off">
<input type="hidden" name="formatting" autocomplete="off">
<input type="hidden" name="preview" autocomplete="off">
</form>

<ul class="settings ng-scope" role="menu" ng-controller="User as user">
<li>
<a ng-click="user.toggleAutoSave($event)">
<span class="has-checkbox">Auto Save</span>
<span class="toggle-auto-save switch ng-isolate-scope checked" ng-class="{checked: toggleValue}" value="user.profile.enableAutoSave">
  <input type="checkbox" ng-model="toggleValue" class="ng-pristine ng-untouched ng-valid ng-not-empty">
  <small></small>
</span>
</a>
</li>
<li>
<a ng-click="user.toggleWordsCount($event)">
<span class="has-checkbox">Word Count</span>
<span class="toggle-word-count switch ng-isolate-scope checked" ng-class="{checked: toggleValue}" value="user.profile.enableWordsCount">
  <input type="checkbox" ng-model="toggleValue" class="ng-pristine ng-untouched ng-valid ng-not-empty">
  <small></small>
</span>
</a>
</li>
<li>
<a ng-click="user.toggleCharactersCount($event)">
<span class="has-checkbox">Character Count</span>
<span class="toggle-character-count switch ng-isolate-scope checked" ng-class="{checked: toggleValue}" value="user.profile.enableCharactersCount">
  <input type="checkbox" ng-model="toggleValue" class="ng-pristine ng-untouched ng-valid ng-not-empty">
  <small></small>
</span>
</a>
</li>
<li>
<a ng-click="user.toggleScrollSync($event)">
<span class="has-checkbox">Scroll Sync</span>
<span class="toggle-scroll-sync switch ng-isolate-scope" ng-class="{checked: toggleValue}" value="user.profile.enableScrollSync">
  <input type="checkbox" ng-model="toggleValue" class="ng-pristine ng-untouched ng-valid ng-empty">
  <small></small>
</span>
</a>
</li>
<li>
<a><form class="ng-pristine ng-valid ng-valid-min">
<span>Tab Size</span>
<input type="number" ng-model="tabsize" min="1" ng-change="user.storeTabSize()" class="ng-pristine ng-untouched ng-valid ng-not-empty ng-valid-min">
</form></a>
</li>
<li>
<a><form class="ng-pristine ng-valid">
<span>Keybindings</span>
<select ng-model="keybindings" ng-change="user.storeKeybindings()" class="ng-pristine ng-untouched ng-valid ng-not-empty">
<!-- ngRepeat: (key, value) in allKeybindings --><option ng-repeat="(key, value) in allKeybindings" value="Ace" class="ng-binding ng-scope" selected="selected">Ace</option><!-- end ngRepeat: (key, value) in allKeybindings --><option ng-repeat="(key, value) in allKeybindings" value="Vim" class="ng-binding ng-scope">Vim</option><!-- end ngRepeat: (key, value) in allKeybindings --><option ng-repeat="(key, value) in allKeybindings" value="Emacs" class="ng-binding ng-scope">Emacs</option><!-- end ngRepeat: (key, value) in allKeybindings -->
</select>
</form></a>
</li>

<li>
<a target="_blank" href="https://www.markdownguide.org/">
<span>Markdown Help</span>
</a>
</li>
<li>
<a class="toggle-wtf" ng-click="user.showAbout($event)">
<span>WTF is Dillinger?</span>
</a>
</li>
<li>
<a class="toggle-reset" ng-click="user.resetProfile($event)">
<span>Reset Profile</span>
</a>
</li>
</ul>
<div class="wrapper">
<div class="sidebar-wrapper">
<div class="sidebar ng-scope" ng-controller="Documents as document">
<h2 class="sidebar-branding">
<svg viewBox="0 0 85 11" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g id="Desktop---Save-to" sketch:type="MSArtboardGroup" transform="translate(-92.000000, -58.000000)" fill="#FFFFFF">
<g id="Navigation" sketch:type="MSLayerGroup" transform="translate(0.000000, 38.000000)">
<g id="Menu-Item:-Branding" transform="translate(91.000000, 17.000000)" sketch:type="MSShapeGroup">
<path d="M1.17,13 L4.563,13 C7.423,13 9.399,11.011 9.399,8.45 L9.399,8.424 C9.399,5.863 7.423,3.9 4.563,3.9 L1.17,3.9 L1.17,13 Z M2.769,11.544 L2.769,5.356 L4.563,5.356 C6.474,5.356 7.722,6.669 7.722,8.45 L7.722,8.476 C7.722,10.257 6.474,11.544 4.563,11.544 L2.769,11.544 Z M13.047,13 L14.646,13 L14.646,3.9 L13.047,3.9 L13.047,13 Z M18.697,13 L25.08,13 L25.08,11.544 L20.296,11.544 L20.296,3.9 L18.697,3.9 L18.697,13 Z M28.364,13 L34.747,13 L34.747,11.544 L29.963,11.544 L29.963,3.9 L28.364,3.9 L28.364,13 Z M38.122,13 L39.721,13 L39.721,3.9 L38.122,3.9 L38.122,13 Z M43.772,13 L45.345,13 L45.345,6.526 L50.363,13 L51.702,13 L51.702,3.9 L50.129,3.9 L50.129,10.192 L45.254,3.9 L43.772,3.9 L43.772,13 Z M59.978,13.156 C61.59,13.156 62.877,12.506 63.774,11.739 L63.774,7.917 L59.9,7.917 L59.9,9.308 L62.227,9.308 L62.227,11.011 C61.668,11.427 60.888,11.7 60.03,11.7 C58.171,11.7 56.936,10.322 56.936,8.45 L56.936,8.424 C56.936,6.682 58.21,5.213 59.887,5.213 C61.044,5.213 61.733,5.59 62.435,6.188 L63.449,4.979 C62.513,4.186 61.538,3.744 59.952,3.744 C57.209,3.744 55.259,5.902 55.259,8.45 L55.259,8.476 C55.259,11.128 57.131,13.156 59.978,13.156 Z M67.474,13 L74.286,13 L74.286,11.57 L69.073,11.57 L69.073,9.126 L73.636,9.126 L73.636,7.696 L69.073,7.696 L69.073,5.33 L74.221,5.33 L74.221,3.9 L67.474,3.9 L67.474,13 Z M77.804,13 L79.403,13 L79.403,9.828 L81.405,9.828 L83.641,13 L85.526,13 L83.069,9.555 C84.343,9.191 85.24,8.294 85.24,6.799 L85.24,6.773 C85.24,5.98 84.967,5.304 84.486,4.81 C83.901,4.238 83.004,3.9 81.86,3.9 L77.804,3.9 L77.804,13 Z M79.403,8.411 L79.403,5.356 L81.73,5.356 C82.913,5.356 83.615,5.889 83.615,6.864 L83.615,6.89 C83.615,7.813 82.887,8.411 81.743,8.411 L79.403,8.411 Z" id="DILLINGER-2"></path>
</g>
</g>
</g>
</g>
</svg>
</h2>
<nav class="nav nav-sidebar">
<ul class="menu menu-sidebar">
<li class="menu-item menu-item--link-unlink in-sidebar">
<a class="menu-link" ng-click="document.status.linkUnlink = !document.status.linkUnlink">
<span>Services</span> <span class="caret"></span></a>
<ul class="sidebar-list collapse" collapse="document.status.linkUnlink" style="height: 0px;">
<li>
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">Link with
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Bitbucket as bitbucket" class="ng-scope">
<a class="import-bitbucket unlinked" href="https://dillinger.io/redirect/bitbucket">Link with
<span>Bitbucket</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">Link with
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li>
<a href="https://dillinger.io/redirect/medium" class="import-medium unlinked">Link with
<span>Medium</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li>
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">Link with
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li>
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">Link with
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--save-to in-sidebar">
<a class="menu-link" ng-click="document.status.save = !document.status.save">
<span>Save to</span> <span class="caret"></span></a>
<ul class="sidebar-list collapse" collapse="document.status.save" style="height: 0px;">
<li ng-controller="Dropbox as dropbox" class="ng-scope">
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>

<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Medium as medium" class="ng-scope">
<a href="https://dillinger.io/redirect/medium" class="import-medium unlinked">
<span>Medium</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Googledrive as googledrive" class="ng-scope">
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Onedrive as onedrive" class="ng-scope">
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--import-from in-sidebar">
<a class="menu-link" ng-click="document.status.import = !document.status.import">
<span>Import from</span> <span class="caret"></span></a>
<ul class="sidebar-list collapse" collapse="document.status.import" style="height: 0px;">
<li ng-controller="Dropbox as dropbox" class="ng-scope">
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Bitbucket as bitbucket" class="ng-scope">
<a class="import-bitbucket unlinked" href="https://dillinger.io/redirect/bitbucket">
<span>Bitbucket</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Googledrive as googledrive" class="ng-scope">
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Onedrive as onedrive" class="ng-scope">
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="ImportFile as importFile" class="ng-scope">
<a class="linked" ng-click="choose()">
<span>Markdown File</span>
</a>
</li>
<li ng-controller="ImportFile as importFile" class="ng-scope">
<a class="linked" ng-click="choose(&#39;html&#39;)">
<span>HTML File</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--documents in-sidebar">
<a class="menu-link" ng-click="document.status.document = !document.status.document">
<span>Documents</span> <span class="caret"></span></a>
<ul class="documents sidebar-list collapse in" collapse="document.status.document" role="menu" style="height: auto;">
<!-- ngRepeat: document in documents track by document.id --><li ng-repeat="document in documents track by document.id" ng-class="{
    &#39;active&#39;: currentDocument.id === document.id,
    &#39;octocat&#39;: document.isGithubFile
    }" class="ng-scope">
<a ng-click="selectDocument(document)" class="ng-binding">Writing.md</a>
</li><!-- end ngRepeat: document in documents track by document.id --><li ng-repeat="document in documents track by document.id" ng-class="{
    &#39;active&#39;: currentDocument.id === document.id,
    &#39;octocat&#39;: document.isGithubFile
    }" class="ng-scope active">
<a ng-click="selectDocument(document)" class="ng-binding">Week2.md</a>
</li><!-- end ngRepeat: document in documents track by document.id -->
</ul>
</li>
</ul>
</nav>
<a class="btn btn--new" ng-click="createDocument()">New Document</a>
<a class="btn btn--save" ng-click="saveDocument(true)">Save Session</a>
<!-- ngIf: documents.length > 1 --><a class="btn btn--delete ng-scope" ng-click="removeDocument(currentDocument)" ng-if="documents.length &gt; 1">Delete Document</a><!-- end ngIf: documents.length > 1 -->
</div>
</div>
<div class="notification-container">
<div class="notification"></div>
</div>
<div class="page">
<div class="navbar">
<a class="toggle">
  <span></span>
</a>
<h1 class="navbar-brand">
<a class="brand" href="https://dillinger.io/"><svg viewBox="0 0 85 11" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g id="Desktop---Save-to" sketch:type="MSArtboardGroup" transform="translate(-92.000000, -58.000000)" fill="#FFFFFF">
<g id="Navigation" sketch:type="MSLayerGroup" transform="translate(0.000000, 38.000000)">
<g id="Menu-Item:-Branding" transform="translate(91.000000, 17.000000)" sketch:type="MSShapeGroup">
<path d="M1.17,13 L4.563,13 C7.423,13 9.399,11.011 9.399,8.45 L9.399,8.424 C9.399,5.863 7.423,3.9 4.563,3.9 L1.17,3.9 L1.17,13 Z M2.769,11.544 L2.769,5.356 L4.563,5.356 C6.474,5.356 7.722,6.669 7.722,8.45 L7.722,8.476 C7.722,10.257 6.474,11.544 4.563,11.544 L2.769,11.544 Z M13.047,13 L14.646,13 L14.646,3.9 L13.047,3.9 L13.047,13 Z M18.697,13 L25.08,13 L25.08,11.544 L20.296,11.544 L20.296,3.9 L18.697,3.9 L18.697,13 Z M28.364,13 L34.747,13 L34.747,11.544 L29.963,11.544 L29.963,3.9 L28.364,3.9 L28.364,13 Z M38.122,13 L39.721,13 L39.721,3.9 L38.122,3.9 L38.122,13 Z M43.772,13 L45.345,13 L45.345,6.526 L50.363,13 L51.702,13 L51.702,3.9 L50.129,3.9 L50.129,10.192 L45.254,3.9 L43.772,3.9 L43.772,13 Z M59.978,13.156 C61.59,13.156 62.877,12.506 63.774,11.739 L63.774,7.917 L59.9,7.917 L59.9,9.308 L62.227,9.308 L62.227,11.011 C61.668,11.427 60.888,11.7 60.03,11.7 C58.171,11.7 56.936,10.322 56.936,8.45 L56.936,8.424 C56.936,6.682 58.21,5.213 59.887,5.213 C61.044,5.213 61.733,5.59 62.435,6.188 L63.449,4.979 C62.513,4.186 61.538,3.744 59.952,3.744 C57.209,3.744 55.259,5.902 55.259,8.45 L55.259,8.476 C55.259,11.128 57.131,13.156 59.978,13.156 Z M67.474,13 L74.286,13 L74.286,11.57 L69.073,11.57 L69.073,9.126 L73.636,9.126 L73.636,7.696 L69.073,7.696 L69.073,5.33 L74.221,5.33 L74.221,3.9 L67.474,3.9 L67.474,13 Z M77.804,13 L79.403,13 L79.403,9.828 L81.405,9.828 L83.641,13 L85.526,13 L83.069,9.555 C84.343,9.191 85.24,8.294 85.24,6.799 L85.24,6.773 C85.24,5.98 84.967,5.304 84.486,4.81 C83.901,4.238 83.004,3.9 81.86,3.9 L77.804,3.9 L77.804,13 Z M79.403,8.411 L79.403,5.356 L81.73,5.356 C82.913,5.356 83.615,5.889 83.615,6.864 L83.615,6.89 C83.615,7.813 82.887,8.411 81.743,8.411 L79.403,8.411 Z" id="DILLINGER-2"></path>
</g>
</g>
</g>
</g>
</svg>
</a>
</h1>
<div class="ad-container">
</div>
<nav class="nav nav-right">
<ul class="menu menu-utilities">
<li class="menu-item menu-item--export-as has-dropdown" dropdown="">
<a class="dropdown-toggle" dropdown-toggle="" aria-haspopup="true" aria-expanded="false">Preview as <span class="caret"></span></a>
<ul class="dropdown dropdown-menu ng-scope" role="menu" ng-controller="DocumentsExport as export" di-target="preview">
<li>
<a ng-click="export.asHTML()" class="export-html">HTML</a>
</li>
<li>
<a ng-click="export.asStyledHTML()" class="export-styled_html">Styled HTML</a>
</li>
<li>
<a ng-click="export.asMarkdown()" class="export-md">Markdown</a>
</li>
<li>
<a ng-click="export.asPDF()" class="export-pdf">PDF</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--export-as has-dropdown" dropdown="">
<a class="dropdown-toggle" dropdown-toggle="" aria-haspopup="true" aria-expanded="false">Export as <span class="caret"></span></a>
<ul class="dropdown dropdown-menu ng-scope" role="menu" ng-controller="DocumentsExport as export" di-target="_top">
<li>
<a ng-click="export.asHTML()" class="export-html">HTML</a>
</li>
<li>
<a ng-click="export.asStyledHTML()" class="export-styled_html">Styled HTML</a>
</li>
<li>
<a ng-click="export.asMarkdown()" class="export-md">Markdown</a>
</li>
<li>
<a ng-click="export.asPDF()" class="export-pdf">PDF</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--save-to has-dropdown" dropdown="">
<a class="dropdown-toggle" dropdown-toggle="" aria-haspopup="true" aria-expanded="false">Save to <span class="caret"></span></a>
<ul class="dropdown dropdown-menu" role="menu">
<li ng-controller="Dropbox as dropbox" class="ng-scope">
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>

<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Medium as medium" class="ng-scope">
<a href="https://dillinger.io/redirect/medium" class="import-medium unlinked">
<span>Medium</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Googledrive as googledrive" class="ng-scope">
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Onedrive as onedrive" class="ng-scope">
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--import-from has-dropdown" dropdown="">
<a class="dropdown-toggle" dropdown-toggle="" aria-haspopup="true" aria-expanded="false">Import from <span class="caret"></span></a>
<ul class="dropdown dropdown-menu" role="menu">
<li ng-controller="Dropbox as dropbox" class="ng-scope">
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Bitbucket as bitbucket" class="ng-scope">
<a class="import-bitbucket unlinked" href="https://dillinger.io/redirect/bitbucket">
<span>Bitbucket</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Googledrive as googledrive" class="ng-scope">
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Onedrive as onedrive" class="ng-scope">
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="ImportFile as importFile" class="ng-scope">
<a class="linked" ng-click="choose()">
<span>Markdown File</span>
</a>
</li>
<li ng-controller="ImportFile as importFile" class="ng-scope">
<a class="linked" ng-click="choose(&#39;html&#39;)">
<span>HTML File</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item-icon menu-item--preview">
<a class="menu-link menu-link-preview" preview-toggle="">
<i class="icon icon-preview"><svg viewBox="0 0 19 12" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g id="Mobile---Home" sketch:type="MSArtboardGroup" transform="translate(-234.000000, -85.000000)" fill="#D3DBEB">
<g id="Navigation" sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g id="Menu-Item:-Preview" transform="translate(218.000000, 0.000000)" sketch:type="MSShapeGroup">
<g id="Icon:-Preview" transform="translate(17.000000, 20.000000)">
<path d="M8.90526316,0.0311320755 C3.00069474,0.0311320755 -0.0947368421,4.79641509 -0.0947368421,5.55188679 C-0.0947368421,6.30756604 3.00069474,11.0726415 8.90526316,11.0726415 C14.8094526,11.0726415 17.9052632,6.30756604 17.9052632,5.55188679 C17.9052632,4.79641509 14.8094526,0.0311320755 8.90526316,0.0311320755 L8.90526316,0.0311320755 Z M8.90526316,9.79871698 C6.69618947,9.79871698 4.90509474,7.89737736 4.90509474,5.55188679 C4.90509474,3.20639623 6.69618947,1.3050566 8.90526316,1.3050566 C11.1143368,1.3050566 12.9052421,3.20639623 12.9052421,5.55188679 C12.9052421,7.89737736 11.1143368,9.79871698 8.90526316,9.79871698 L8.90526316,9.79871698 Z M10.9051579,5.55188679 C10.9051579,6.7245283 10.0095158,7.67550943 8.90526316,7.67550943 C7.80063158,7.67550943 6.90536842,6.7245283 6.90536842,5.55188679 C6.90536842,4.37924528 7.80063158,3.4284717 8.90526316,3.4284717 C9.50210526,3.4284717 8.53901053,5.11126415 8.90526316,5.55188679 C9.21656842,5.92609434 10.9051579,5.01330189 10.9051579,5.55188679 L10.9051579,5.55188679 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</svg>
</i>
<span class="sr-only">Preview</span>
</a>
</li>
<li class="menu-item menu-item-icon menu-item--settings">
<a class="menu-link menu-link-settings" settings-toggle="">
<i class="icon icon-settings"><svg viewBox="0 0 18 18" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g id="Mobile---Home" sketch:type="MSArtboardGroup" transform="translate(-286.000000, -81.000000)" fill="#D3DBEB">
<g id="Navigation" sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g id="Menu-Item:-Settings" transform="translate(269.000000, 0.000000)" sketch:type="MSShapeGroup">
<g id="Icon:-Settings" transform="translate(17.000000, 16.000000)">
<path d="M17.341654,7.68935491 L15.5585491,7.39189286 C15.4289531,6.86205804 15.2399933,6.35558705 14.9938996,5.88320759 L16.1353929,4.46787723 C16.3781719,4.16876786 16.3671429,3.73839509 16.1111853,3.44971205 L15.4020134,2.65156473 C15.1449509,2.36318304 14.7186763,2.30219196 14.3934911,2.507625 L12.8685937,3.46620536 C12.1978929,2.99760268 11.4381562,2.65156473 10.6185937,2.45077232 L10.3202679,0.658104911 C10.2576696,0.278517857 9.92918973,0 9.54359598,0 L8.47488616,0 C8.09007589,0 7.76049107,0.278517857 7.69925893,0.658104911 L7.39932589,2.45133482 C6.72173437,2.61723214 6.0864308,2.88502232 5.50665402,3.23770982 L4.05644866,2.20275 C3.74389955,1.97945759 3.31461161,2.01437277 3.04185937,2.28654241 L2.28684375,3.04210045 C2.01467411,3.31485268 1.97975893,3.74414062 2.20363393,4.05668973 L3.24100446,5.50966741 C2.8916317,6.08506473 2.62659375,6.71675223 2.46071652,7.38829687 L0.65784375,7.68935491 C0.278839286,7.75195312 -0.000220982143,8.08047321 -0.000220982143,8.46606696 L-0.000220982143,9.53393304 C-0.000220982143,9.91952679 0.278839286,10.2480469 0.65784375,10.3106451 L2.46071652,10.6117031 C2.59694196,11.1642991 2.79470089,11.6921853 3.05754911,12.1816205 L1.92125893,13.5889554 C1.67930357,13.8877835 1.68946875,14.3184375 1.94542634,14.6068594 L2.6540558,15.4050067 C2.91113839,15.6939308 3.33765402,15.753817 3.66285937,15.5489063 L5.20973437,14.5771875 C5.86426339,15.0248772 6.60473437,15.3539196 7.39932589,15.5489063 L7.69925893,17.341875 C7.76049107,17.7215022 8.09007589,18 8.47488616,18 L9.54359598,18 C9.92918973,18 10.2576696,17.7215022 10.3202679,17.3418951 L10.619096,15.5489263 C11.2882299,15.3852589 11.9154777,15.1221295 12.4900915,14.7754888 L14.0007254,15.8543839 C14.3127321,16.0785 14.7423214,16.0433437 15.0147924,15.7703103 L15.7700893,15.0150134 C16.0419576,14.7430848 16.0787812,14.3140379 15.8529978,14.0009464 L14.7774978,12.4930647 C15.1278951,11.9157388 15.3943192,11.2829263 15.5591518,10.6083683 L17.3422366,10.310625 C17.722346,10.2480268 18.0002812,9.9195067 18.0002812,9.53391295 L18.0002812,8.46604688 C17.9997388,8.08047321 17.7218036,7.75195312 17.341654,7.68935491 L17.341654,7.68935491 Z M9.0283058,12.375 C7.1647433,12.375 5.6533058,10.8632812 5.6533058,9 C5.6533058,7.1364375 7.1647433,5.625 9.0283058,5.625 C10.8915469,5.625 12.4032656,7.1364375 12.4032656,9 C12.4032656,10.8632812 10.8915469,12.375 9.0283058,12.375 L9.0283058,12.375 Z" id="settings_1_"></path>
</g>
</g>
</g>
</g>
</g>
</svg>
</i>
<span class="sr-only">Settings</span>
</a>
</li>
</ul>
 </nav>
</div>
<div class="overlay"></div>
<div class="header">
<h2 class="title">Document Name</h2>
<document-title><input class="title-document ng-pristine ng-untouched ng-valid ng-not-empty" type="text" name="documentTitle" ng-change="updateDocument()" ng-model-options="{ debounce: 500 }" ng-model="currentDocument.title">
</document-title>
<!-- ngIf: profile.enableWordsCount && !viewSrcMode --><p ng-if="profile.enableWordsCount &amp;&amp; !viewSrcMode" class="words ng-scope">
<span class="mr10">Reading Time: <span class="counter ng-binding" ng-bind="readingTime">5 min read</span></span>
<span>Words: <span class="counter ng-binding" ng-bind="words">893</span></span>
</p><!-- end ngIf: profile.enableWordsCount && !viewSrcMode -->
<!-- ngIf: profile.enableCharactersCount && !viewSrcMode --><p ng-if="profile.enableCharactersCount &amp;&amp; !viewSrcMode" class="characters ng-scope">Characters: <span class="counter ng-binding" ng-bind="characters">8939</span></p><!-- end ngIf: profile.enableCharactersCount && !viewSrcMode -->
</div>
<div class="g mnone">
<div class="editor-header editor-header--first">
<h3 class="title">Markdown</h3>
<!-- ngIf: !$root.viewSrcMode --><a class="enter-zen-mode ng-scope" ng-click="zenmode.toggle()" ng-if="!$root.viewSrcMode">Toggle Zen Mode</a><!-- end ngIf: !$root.viewSrcMode -->
</div>
<div class="editor-header">
<h3 class="title">Preview</h3>
<a ng-class="{&#39;preview-mode-toggle-html&#39; : $root.viewSrcMode, &#39;preview-mode-toggle-src&#39; : !$root.viewSrcMode}" ng-click="toggleView()" class="preview-mode-toggle-src">Toggle Mode</a>
</div>
<div id="editor1" class="g-b g-b--t1of2 split split-editor" style="height: 484px;">
<div id="editor" class="ui-resizable-e ace_editor ace-tm ace_focus" style="height: 10948px;"><textarea class="ace_text-input" wrap="off" autocorrect="off" autocapitalize="off" spellcheck="false" style="opacity: 0; left: 72px; top: 10892px; height: 28px; width: 7px;"></textarea><div class="ace_gutter" aria-hidden="true"><div class="ace_layer ace_gutter-layer ace_folding-enabled" style="margin-top: 0px; height: 11004px; width: 54px;"><div class="ace_gutter-cell " style="height: 28px;">1<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">2<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">3<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">4<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">5<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">6</div><div class="ace_gutter-cell " style="height: 28px;">7</div><div class="ace_gutter-cell " style="height: 28px;">8<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 56px;">9</div><div class="ace_gutter-cell " style="height: 28px;">10</div><div class="ace_gutter-cell " style="height: 28px;">11</div><div class="ace_gutter-cell " style="height: 56px;">12</div><div class="ace_gutter-cell " style="height: 28px;">13</div><div class="ace_gutter-cell " style="height: 28px;">14<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">15</div><div class="ace_gutter-cell " style="height: 28px;">16</div><div class="ace_gutter-cell " style="height: 28px;">17</div><div class="ace_gutter-cell " style="height: 28px;">18</div><div class="ace_gutter-cell " style="height: 28px;">19</div><div class="ace_gutter-cell " style="height: 28px;">20</div><div class="ace_gutter-cell " style="height: 28px;">21</div><div class="ace_gutter-cell " style="height: 28px;">22<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">23</div><div class="ace_gutter-cell " style="height: 28px;">24</div><div class="ace_gutter-cell " style="height: 56px;">25</div><div class="ace_gutter-cell " style="height: 28px;">26</div><div class="ace_gutter-cell " style="height: 28px;">27<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">28</div><div class="ace_gutter-cell " style="height: 28px;">29</div><div class="ace_gutter-cell " style="height: 28px;">30</div><div class="ace_gutter-cell " style="height: 28px;">31</div><div class="ace_gutter-cell " style="height: 28px;">32</div><div class="ace_gutter-cell " style="height: 28px;">33</div><div class="ace_gutter-cell " style="height: 28px;">34</div><div class="ace_gutter-cell " style="height: 28px;">35</div><div class="ace_gutter-cell " style="height: 28px;">36</div><div class="ace_gutter-cell " style="height: 28px;">37</div><div class="ace_gutter-cell " style="height: 28px;">38</div><div class="ace_gutter-cell " style="height: 28px;">39</div><div class="ace_gutter-cell " style="height: 28px;">40</div><div class="ace_gutter-cell " style="height: 28px;">41</div><div class="ace_gutter-cell " style="height: 28px;">42</div><div class="ace_gutter-cell " style="height: 28px;">43</div><div class="ace_gutter-cell " style="height: 28px;">44<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">45</div><div class="ace_gutter-cell " style="height: 28px;">46</div><div class="ace_gutter-cell " style="height: 28px;">47</div><div class="ace_gutter-cell " style="height: 28px;">48</div><div class="ace_gutter-cell " style="height: 28px;">49<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">50</div><div class="ace_gutter-cell " style="height: 28px;">51</div><div class="ace_gutter-cell " style="height: 28px;">52</div><div class="ace_gutter-cell " style="height: 28px;">53</div><div class="ace_gutter-cell " style="height: 28px;">54</div><div class="ace_gutter-cell " style="height: 28px;">55</div><div class="ace_gutter-cell " style="height: 28px;">56</div><div class="ace_gutter-cell " style="height: 28px;">57</div><div class="ace_gutter-cell " style="height: 28px;">58</div><div class="ace_gutter-cell " style="height: 28px;">59</div><div class="ace_gutter-cell " style="height: 28px;">60</div><div class="ace_gutter-cell " style="height: 28px;">61</div><div class="ace_gutter-cell " style="height: 28px;">62</div><div class="ace_gutter-cell " style="height: 28px;">63<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">64</div><div class="ace_gutter-cell " style="height: 28px;">65</div><div class="ace_gutter-cell " style="height: 84px;">66</div><div class="ace_gutter-cell " style="height: 28px;">67</div><div class="ace_gutter-cell " style="height: 28px;">68<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">69</div><div class="ace_gutter-cell " style="height: 28px;">70</div><div class="ace_gutter-cell " style="height: 28px;">71</div><div class="ace_gutter-cell " style="height: 28px;">72<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">73</div><div class="ace_gutter-cell " style="height: 28px;">74</div><div class="ace_gutter-cell " style="height: 28px;">75<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">76</div><div class="ace_gutter-cell " style="height: 28px;">77</div><div class="ace_gutter-cell " style="height: 28px;">78</div><div class="ace_gutter-cell " style="height: 28px;">79<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">80</div><div class="ace_gutter-cell " style="height: 28px;">81</div><div class="ace_gutter-cell " style="height: 28px;">82<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">83</div><div class="ace_gutter-cell " style="height: 28px;">84</div><div class="ace_gutter-cell " style="height: 28px;">85</div><div class="ace_gutter-cell " style="height: 28px;">86<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">87</div><div class="ace_gutter-cell " style="height: 28px;">88<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">89</div><div class="ace_gutter-cell " style="height: 28px;">90</div><div class="ace_gutter-cell " style="height: 28px;">91</div><div class="ace_gutter-cell " style="height: 28px;">92</div><div class="ace_gutter-cell " style="height: 28px;">93</div><div class="ace_gutter-cell " style="height: 28px;">94</div><div class="ace_gutter-cell " style="height: 28px;">95</div><div class="ace_gutter-cell " style="height: 28px;">96</div><div class="ace_gutter-cell " style="height: 28px;">97</div><div class="ace_gutter-cell " style="height: 28px;">98</div><div class="ace_gutter-cell " style="height: 28px;">99</div><div class="ace_gutter-cell " style="height: 28px;">100</div><div class="ace_gutter-cell " style="height: 56px;">101</div><div class="ace_gutter-cell " style="height: 28px;">102</div><div class="ace_gutter-cell " style="height: 28px;">103<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">104</div><div class="ace_gutter-cell " style="height: 28px;">105</div><div class="ace_gutter-cell " style="height: 28px;">106</div><div class="ace_gutter-cell " style="height: 28px;">107</div><div class="ace_gutter-cell " style="height: 28px;">108<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">109</div><div class="ace_gutter-cell " style="height: 28px;">110<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">111</div><div class="ace_gutter-cell " style="height: 56px;">112</div><div class="ace_gutter-cell " style="height: 56px;">113</div><div class="ace_gutter-cell " style="height: 28px;">114</div><div class="ace_gutter-cell " style="height: 28px;">115</div><div class="ace_gutter-cell " style="height: 28px;">116</div><div class="ace_gutter-cell " style="height: 28px;">117</div><div class="ace_gutter-cell " style="height: 28px;">118</div><div class="ace_gutter-cell " style="height: 28px;">119</div><div class="ace_gutter-cell " style="height: 28px;">120</div><div class="ace_gutter-cell " style="height: 28px;">121</div><div class="ace_gutter-cell " style="height: 28px;">122</div><div class="ace_gutter-cell " style="height: 28px;">123</div><div class="ace_gutter-cell " style="height: 28px;">124</div><div class="ace_gutter-cell " style="height: 28px;">125</div><div class="ace_gutter-cell " style="height: 28px;">126</div><div class="ace_gutter-cell " style="height: 28px;">127</div><div class="ace_gutter-cell " style="height: 28px;">128</div><div class="ace_gutter-cell " style="height: 28px;">129</div><div class="ace_gutter-cell " style="height: 28px;">130</div><div class="ace_gutter-cell " style="height: 28px;">131</div><div class="ace_gutter-cell " style="height: 28px;">132<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 56px;">133</div><div class="ace_gutter-cell " style="height: 28px;">134</div><div class="ace_gutter-cell " style="height: 28px;">135<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">136</div><div class="ace_gutter-cell " style="height: 28px;">137</div><div class="ace_gutter-cell " style="height: 28px;">138</div><div class="ace_gutter-cell " style="height: 28px;">139</div><div class="ace_gutter-cell " style="height: 28px;">140</div><div class="ace_gutter-cell " style="height: 28px;">141</div><div class="ace_gutter-cell " style="height: 28px;">142</div><div class="ace_gutter-cell " style="height: 28px;">143</div><div class="ace_gutter-cell " style="height: 28px;">144</div><div class="ace_gutter-cell " style="height: 28px;">145</div><div class="ace_gutter-cell " style="height: 28px;">146</div><div class="ace_gutter-cell " style="height: 28px;">147</div><div class="ace_gutter-cell " style="height: 28px;">148</div><div class="ace_gutter-cell " style="height: 28px;">149</div><div class="ace_gutter-cell " style="height: 28px;">150</div><div class="ace_gutter-cell " style="height: 28px;">151</div><div class="ace_gutter-cell " style="height: 28px;">152</div><div class="ace_gutter-cell " style="height: 28px;">153</div><div class="ace_gutter-cell " style="height: 28px;">154</div><div class="ace_gutter-cell " style="height: 28px;">155</div><div class="ace_gutter-cell " style="height: 28px;">156</div><div class="ace_gutter-cell " style="height: 28px;">157</div><div class="ace_gutter-cell " style="height: 28px;">158</div><div class="ace_gutter-cell " style="height: 28px;">159</div><div class="ace_gutter-cell " style="height: 28px;">160</div><div class="ace_gutter-cell " style="height: 28px;">161<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">162</div><div class="ace_gutter-cell " style="height: 28px;">163<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">164</div><div class="ace_gutter-cell " style="height: 28px;">165</div><div class="ace_gutter-cell " style="height: 28px;">166</div><div class="ace_gutter-cell " style="height: 28px;">167</div><div class="ace_gutter-cell " style="height: 28px;">168</div><div class="ace_gutter-cell " style="height: 28px;">169</div><div class="ace_gutter-cell " style="height: 28px;">170</div><div class="ace_gutter-cell " style="height: 28px;">171</div><div class="ace_gutter-cell " style="height: 28px;">172</div><div class="ace_gutter-cell " style="height: 28px;">173</div><div class="ace_gutter-cell " style="height: 28px;">174</div><div class="ace_gutter-cell " style="height: 28px;">175</div><div class="ace_gutter-cell " style="height: 28px;">176</div><div class="ace_gutter-cell " style="height: 28px;">177</div><div class="ace_gutter-cell " style="height: 28px;">178</div><div class="ace_gutter-cell " style="height: 28px;">179</div><div class="ace_gutter-cell " style="height: 28px;">180</div><div class="ace_gutter-cell " style="height: 28px;">181</div><div class="ace_gutter-cell " style="height: 28px;">182</div><div class="ace_gutter-cell " style="height: 28px;">183</div><div class="ace_gutter-cell " style="height: 28px;">184</div><div class="ace_gutter-cell " style="height: 28px;">185</div><div class="ace_gutter-cell " style="height: 28px;">186</div><div class="ace_gutter-cell " style="height: 28px;">187</div><div class="ace_gutter-cell " style="height: 28px;">188</div><div class="ace_gutter-cell " style="height: 28px;">189</div><div class="ace_gutter-cell " style="height: 28px;">190</div><div class="ace_gutter-cell " style="height: 28px;">191</div><div class="ace_gutter-cell " style="height: 28px;">192</div><div class="ace_gutter-cell " style="height: 28px;">193</div><div class="ace_gutter-cell " style="height: 28px;">194</div><div class="ace_gutter-cell " style="height: 28px;">195</div><div class="ace_gutter-cell " style="height: 28px;">196</div><div class="ace_gutter-cell " style="height: 28px;">197</div><div class="ace_gutter-cell " style="height: 28px;">198</div><div class="ace_gutter-cell " style="height: 28px;">199</div><div class="ace_gutter-cell " style="height: 28px;">200</div><div class="ace_gutter-cell " style="height: 28px;">201</div><div class="ace_gutter-cell " style="height: 28px;">202</div><div class="ace_gutter-cell " style="height: 28px;">203</div><div class="ace_gutter-cell " style="height: 28px;">204</div><div class="ace_gutter-cell " style="height: 28px;">205</div><div class="ace_gutter-cell " style="height: 28px;">206<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">207</div><div class="ace_gutter-cell " style="height: 28px;">208<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">209</div><div class="ace_gutter-cell " style="height: 28px;">210<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">211</div><div class="ace_gutter-cell " style="height: 28px;">212</div><div class="ace_gutter-cell " style="height: 28px;">213</div><div class="ace_gutter-cell " style="height: 28px;">214</div><div class="ace_gutter-cell " style="height: 28px;">215</div><div class="ace_gutter-cell " style="height: 28px;">216</div><div class="ace_gutter-cell " style="height: 28px;">217</div><div class="ace_gutter-cell " style="height: 28px;">218</div><div class="ace_gutter-cell " style="height: 28px;">219</div><div class="ace_gutter-cell " style="height: 28px;">220</div><div class="ace_gutter-cell " style="height: 28px;">221</div><div class="ace_gutter-cell " style="height: 28px;">222</div><div class="ace_gutter-cell " style="height: 28px;">223</div><div class="ace_gutter-cell " style="height: 28px;">224</div><div class="ace_gutter-cell " style="height: 28px;">225</div><div class="ace_gutter-cell " style="height: 28px;">226</div><div class="ace_gutter-cell " style="height: 28px;">227</div><div class="ace_gutter-cell " style="height: 28px;">228</div><div class="ace_gutter-cell " style="height: 28px;">229</div><div class="ace_gutter-cell " style="height: 28px;">230<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">231</div><div class="ace_gutter-cell " style="height: 28px;">232<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">233</div><div class="ace_gutter-cell " style="height: 28px;">234</div><div class="ace_gutter-cell " style="height: 28px;">235</div><div class="ace_gutter-cell " style="height: 28px;">236</div><div class="ace_gutter-cell " style="height: 28px;">237</div><div class="ace_gutter-cell " style="height: 28px;">238</div><div class="ace_gutter-cell " style="height: 28px;">239</div><div class="ace_gutter-cell " style="height: 28px;">240</div><div class="ace_gutter-cell " style="height: 28px;">241</div><div class="ace_gutter-cell " style="height: 28px;">242</div><div class="ace_gutter-cell " style="height: 28px;">243</div><div class="ace_gutter-cell " style="height: 28px;">244</div><div class="ace_gutter-cell " style="height: 28px;">245</div><div class="ace_gutter-cell " style="height: 28px;">246</div><div class="ace_gutter-cell " style="height: 28px;">247</div><div class="ace_gutter-cell " style="height: 28px;">248</div><div class="ace_gutter-cell " style="height: 28px;">249</div><div class="ace_gutter-cell " style="height: 28px;">250</div><div class="ace_gutter-cell " style="height: 28px;">251</div><div class="ace_gutter-cell " style="height: 28px;">252</div><div class="ace_gutter-cell " style="height: 28px;">253</div><div class="ace_gutter-cell " style="height: 28px;">254</div><div class="ace_gutter-cell " style="height: 28px;">255</div><div class="ace_gutter-cell " style="height: 28px;">256</div><div class="ace_gutter-cell " style="height: 28px;">257</div><div class="ace_gutter-cell " style="height: 28px;">258</div><div class="ace_gutter-cell " style="height: 28px;">259</div><div class="ace_gutter-cell " style="height: 28px;">260</div><div class="ace_gutter-cell " style="height: 28px;">261<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">262</div><div class="ace_gutter-cell " style="height: 28px;">263</div><div class="ace_gutter-cell " style="height: 28px;">264<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">265</div><div class="ace_gutter-cell " style="height: 28px;">266</div><div class="ace_gutter-cell " style="height: 28px;">267</div><div class="ace_gutter-cell " style="height: 28px;">268</div><div class="ace_gutter-cell " style="height: 28px;">269</div><div class="ace_gutter-cell " style="height: 28px;">270</div><div class="ace_gutter-cell " style="height: 28px;">271</div><div class="ace_gutter-cell " style="height: 28px;">272</div><div class="ace_gutter-cell " style="height: 28px;">273</div><div class="ace_gutter-cell " style="height: 28px;">274</div><div class="ace_gutter-cell " style="height: 28px;">275</div><div class="ace_gutter-cell " style="height: 28px;">276</div><div class="ace_gutter-cell " style="height: 28px;">277</div><div class="ace_gutter-cell " style="height: 28px;">278</div><div class="ace_gutter-cell " style="height: 28px;">279</div><div class="ace_gutter-cell " style="height: 28px;">280</div><div class="ace_gutter-cell " style="height: 28px;">281</div><div class="ace_gutter-cell " style="height: 28px;">282</div><div class="ace_gutter-cell " style="height: 28px;">283<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">284</div><div class="ace_gutter-cell " style="height: 28px;">285</div><div class="ace_gutter-cell " style="height: 28px;">286<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">287</div><div class="ace_gutter-cell " style="height: 28px;">288</div><div class="ace_gutter-cell " style="height: 28px;">289</div><div class="ace_gutter-cell " style="height: 28px;">290</div><div class="ace_gutter-cell " style="height: 28px;">291</div><div class="ace_gutter-cell " style="height: 28px;">292</div><div class="ace_gutter-cell " style="height: 28px;">293</div><div class="ace_gutter-cell " style="height: 28px;">294</div><div class="ace_gutter-cell " style="height: 28px;">295</div><div class="ace_gutter-cell " style="height: 28px;">296</div><div class="ace_gutter-cell " style="height: 28px;">297</div><div class="ace_gutter-cell " style="height: 28px;">298</div><div class="ace_gutter-cell " style="height: 28px;">299</div><div class="ace_gutter-cell " style="height: 28px;">300</div><div class="ace_gutter-cell " style="height: 28px;">301</div><div class="ace_gutter-cell " style="height: 28px;">302</div><div class="ace_gutter-cell " style="height: 28px;">303</div><div class="ace_gutter-cell " style="height: 28px;">304</div><div class="ace_gutter-cell " style="height: 28px;">305<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">306</div><div class="ace_gutter-cell " style="height: 28px;">307</div><div class="ace_gutter-cell " style="height: 28px;">308<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">309</div><div class="ace_gutter-cell " style="height: 28px;">310</div><div class="ace_gutter-cell " style="height: 28px;">311</div><div class="ace_gutter-cell " style="height: 28px;">312</div><div class="ace_gutter-cell " style="height: 28px;">313</div><div class="ace_gutter-cell " style="height: 28px;">314</div><div class="ace_gutter-cell " style="height: 28px;">315</div><div class="ace_gutter-cell " style="height: 28px;">316</div><div class="ace_gutter-cell " style="height: 28px;">317</div><div class="ace_gutter-cell " style="height: 28px;">318</div><div class="ace_gutter-cell " style="height: 28px;">319</div><div class="ace_gutter-cell " style="height: 28px;">320</div><div class="ace_gutter-cell " style="height: 28px;">321</div><div class="ace_gutter-cell " style="height: 28px;">322</div><div class="ace_gutter-cell " style="height: 28px;">323</div><div class="ace_gutter-cell " style="height: 28px;">324</div><div class="ace_gutter-cell " style="height: 28px;">325</div><div class="ace_gutter-cell " style="height: 28px;">326</div><div class="ace_gutter-cell " style="height: 28px;">327</div><div class="ace_gutter-cell " style="height: 28px;">328</div><div class="ace_gutter-cell " style="height: 28px;">329</div><div class="ace_gutter-cell " style="height: 28px;">330</div><div class="ace_gutter-cell " style="height: 28px;">331</div><div class="ace_gutter-cell " style="height: 28px;">332</div><div class="ace_gutter-cell " style="height: 28px;">333</div><div class="ace_gutter-cell " style="height: 28px;">334</div><div class="ace_gutter-cell " style="height: 28px;">335</div><div class="ace_gutter-cell " style="height: 28px;">336</div><div class="ace_gutter-cell " style="height: 28px;">337</div><div class="ace_gutter-cell " style="height: 28px;">338</div><div class="ace_gutter-cell " style="height: 28px;">339<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">340</div><div class="ace_gutter-cell " style="height: 28px;">341</div><div class="ace_gutter-cell " style="height: 28px;">342<span class="ace_fold-widget ace_start ace_open" style="height: 28px;"></span></div><div class="ace_gutter-cell " style="height: 28px;">343</div><div class="ace_gutter-cell " style="height: 28px;">344</div><div class="ace_gutter-cell " style="height: 28px;">345</div><div class="ace_gutter-cell " style="height: 28px;">346</div><div class="ace_gutter-cell " style="height: 28px;">347</div><div class="ace_gutter-cell " style="height: 28px;">348</div><div class="ace_gutter-cell " style="height: 28px;">349</div><div class="ace_gutter-cell " style="height: 28px;">350</div><div class="ace_gutter-cell " style="height: 28px;">351</div><div class="ace_gutter-cell " style="height: 28px;">352</div><div class="ace_gutter-cell " style="height: 28px;">353</div><div class="ace_gutter-cell " style="height: 28px;">354</div><div class="ace_gutter-cell " style="height: 28px;">355</div><div class="ace_gutter-cell " style="height: 28px;">356</div><div class="ace_gutter-cell " style="height: 28px;">357</div><div class="ace_gutter-cell " style="height: 28px;">358</div><div class="ace_gutter-cell " style="height: 28px;">359</div><div class="ace_gutter-cell " style="height: 28px;">360</div><div class="ace_gutter-cell " style="height: 28px;">361</div><div class="ace_gutter-cell " style="height: 28px;">362</div><div class="ace_gutter-cell " style="height: 28px;">363</div><div class="ace_gutter-cell " style="height: 28px;">364</div><div class="ace_gutter-cell " style="height: 28px;">365</div><div class="ace_gutter-cell " style="height: 28px;">366</div><div class="ace_gutter-cell " style="height: 28px;">367</div><div class="ace_gutter-cell " style="height: 28px;">368</div><div class="ace_gutter-cell " style="height: 28px;">369</div><div class="ace_gutter-cell " style="height: 28px;">370</div><div class="ace_gutter-cell " style="height: 28px;">371</div><div class="ace_gutter-cell " style="height: 28px;">372</div><div class="ace_gutter-cell " style="height: 28px;">373</div><div class="ace_gutter-cell " style="height: 28px;">374</div><div class="ace_gutter-cell " style="height: 28px;">375</div><div class="ace_gutter-cell " style="height: 28px;">376</div><div class="ace_gutter-cell " style="height: 28px;">377</div><div class="ace_gutter-cell " style="height: 28px;">378</div><div class="ace_gutter-cell " style="height: 28px;">379</div><div class="ace_gutter-cell " style="height: 28px;">380</div><div class="ace_gutter-cell " style="height: 28px;">381</div><div class="ace_gutter-cell " style="height: 28px;">382<span class="ace_fold-widget ace_end ace_open" style="height: 28px;"></span></div></div><div class="ace_gutter-active-line" style="top: 10892px; height: 28px;"></div></div><div class="ace_scroller" style="left: 54px; right: 0px; bottom: 0px;"><div class="ace_content" style="margin-top: 0px; width: 687px; height: 11004px; margin-left: 0px;"><div class="ace_layer ace_print-margin-layer"><div class="ace_print-margin" style="left: 564px; visibility: hidden;"></div></div><div class="ace_layer ace_marker-layer"><div class="ace_active-line" style="height:28px;top:10892px;left:0;right:0;"></div><div class="ace_bracket ace_start ace_br15" style="height:28px;width:7px;top:10080px;left:186px;"></div></div><div class="ace_layer ace_text-layer" style="padding: 0px 4px;"><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> Nama : Muh. Faizal Rajib</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> Learning Track : Front-End Develovment</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> Challeng Patner : Serrum Gudskul</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> Kelompok : FE 25</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> Week 2</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">.</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> </span><span class="ace_string ace_strong">**Day 1 Looping**</span></div></div><div class="ace_line_group" style="height:56px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Looping Looping adalah sebuah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi </span></div><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">atau jika kondisi berhenti/stop tercapai.</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Perulangan For Loop</span></div></div><div class="ace_line_group" style="height:56px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**For Loop**</span><span class="ace_text ace_xml"> Merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita </span></div><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">kembangkan. for loop memiliki aturan tersendiri dalam penulisannya.</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">contohnya: </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    for (let i = 1; i &lt;= 10 ; i++){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        if (i == 6) {</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        console.log(i, "Yes Ketemu")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        } else {</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        console.log(i); </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Perulangan While </span></div></div><div class="ace_line_group" style="height:56px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**Perulang While**</span><span class="ace_text ace_xml"> merupakan perulangan yang bersifat indefinite alias tidak pasti, atau bahkan </span></div><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">tidak terbatas.</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Contohnya : </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let i = 1;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let isKetemu = false</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    while(!isKetemu){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        if(</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 2 == 0 &amp;&amp;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 3 == 0 &amp;&amp;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 4 == 0 &amp;&amp;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 5 == 0 &amp;&amp;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 6 == 0</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        ){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        console.log(i);</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        isKetemu = true</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        i++</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Perulangan Do While </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**Perulangan Do While**</span><span class="ace_text ace_xml"> melakukan perulangan dulu, kemudian memeriksa kondisinya atau sayaratnya.</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Contohnya :</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    do{</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        if(</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 2 == 0 &amp;&amp;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 3 == 0 &amp;&amp;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 4 == 0 &amp;&amp;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 5 == 0 &amp;&amp;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        i % 6 == 0</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        ){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        console.log(i);</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">        isKetemu = true</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">        i++</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    } while (!isKetemu)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**Function**</span></div></div><div class="ace_line_group" style="height:84px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Function adalah kode program yang dirancang untuk menyelesaikan sebuah tugas tertentu, dan </span></div><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">merupakan bagian dari program utama. Ketika di sadur ke dalam bahasa indonesia, function ini di </span></div><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">sebut juga sebagai fungsi. Ada beberapa penulisan function :</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">1. </span><span class="ace_list">function classic</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    function myFuction (parameter) {</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    //Perintah yang dijalankan</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    } </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">2. </span><span class="ace_list">Arrow function</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let myFunction = () =&gt; {</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    //kode yang dijalankan</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">3. </span><span class="ace_list">function variable</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let myFuction = function (){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    //kode yang akan dijalankan</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> </span><span class="ace_string ace_strong">**Day 2 Type Data**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Ada beberapa type data</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**Primitive**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">1. </span><span class="ace_list">String</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">2. </span><span class="ace_list">Number</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">3. </span><span class="ace_list">Bolean</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**Non-Primitive**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">1. </span><span class="ace_list">Array</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">2. </span><span class="ace_list">Method</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**String**</span></div></div><div class="ace_line_group" style="height:56px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Nilai dari type data ini selalu dibungkus dengan tanda kutip 2 ("Nilai dari string"), jadi segala </span></div><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">sesuatu yang bungkus oleh tanda kutip 2 ini akan di baca String walaupun itu angka.</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Penulisan String :</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let hewan = "Kancil";</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log("Ini adalah " + hewan);</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log(`Ini adalah ${hewan}`);</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> </span><span class="ace_string ace_strong">**Day 3 DOM**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">DOM (Document Object Model) adalah dokumen (HTML) yang dimodelkan dalam sebuah objek.</span></div></div><div class="ace_line_group" style="height:56px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">DOM adalah jembatan supaya bahasa pemrograman dapat berinteraksi dengan dokumen HTML, dengan DOM, </span></div><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">JS dapat memanipulasi HTML.</span></div></div><div class="ace_line_group" style="height:56px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">DOM bukan merupakan bahasa JavaScript. Tapi merupakan web API untuk membuat website cara akses </span></div><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">nya menggunakan JavaScript. DOM tidak bisa digunakan pada Server.</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**Traversing**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Kebawah: </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">1. </span><span class="ace_list">getElementById</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">2. </span><span class="ace_list">getElementsByClassName</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">3. </span><span class="ace_list">getElementsByTagName</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">4. </span><span class="ace_list">querySelectoriFamily</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">5. </span><span class="ace_list">childern</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Keatas:</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">1. </span><span class="ace_list">parentElement</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">2. </span><span class="ace_list">closest()</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">kesamping</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">1. </span><span class="ace_list">nextElementSibling</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_list">2. </span><span class="ace_list">previousElementSibling</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">HTML Collection</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> </span><span class="ace_string ace_strong">**Day 4 DOM Manipulation**</span></div></div><div class="ace_line_group" style="height:56px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">DOM Manipulation berinteraksi dengan DOM API untuk mengubah/memodifikasi dokumen HTML yang akan </span></div><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">dirender di browser web.</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">contoh index.html :</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;!DOCTYPE html&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;html lang="en"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;head&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;meta charset="UTF-8"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;title&gt;Document&lt;/title&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;style&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    #tess{</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    width: 100px;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    height: 20px;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    background-color: brown;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;/style&gt;    </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;/head&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;body&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;div id="tess"&gt;&lt;/div&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;div id="app"&gt;&lt;/div&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;div id="end"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;a href="google.com" class="link"&gt;Google&lt;/a&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;/div&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;script src="script.js"&gt;&lt;/script&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;/body&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;/html&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">Contoh scrip.js: </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let app = document.getElementById("app")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log(app)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    //tag htmlnya akan di baca sebagai perintah</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    app.innerHTML = "&lt;h1&gt;Hallo&lt;/h1&gt;"  </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    //walaupun itu element html akan tetap dibaca text</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    // app.innerText = "&lt;h1&gt;Apa Kabar&lt;/h1&gt;" </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let p = document.createElement("p")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    p.innerText = "Ini adalah paragraf";</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    app.append(p)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    // console.log(p);</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let p2 = document.createElement("p")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    p2.innerText = "paragraf ke-2"</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    app.appendChild(p2)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    //appendChild tidak bisa input data string</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    app.append("menggunakan append")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    // app.appendChild("appendChild")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let end = document.getElementById("end")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    //end.remove</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let link = document.getElementsByClassName("link")[0]</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log(link.attributes)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log(link.getAttribute("href"));</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    link.setAttribute("id","google")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    link.style.color ="black"</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    link.style.border = "1px solid black"</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    link.style.padding = "5px 20px"</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    link.style.backgroundColor = "aqua"</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let tess = document.getElementById("tess")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let tessStyle = getComputedStyle(tess)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log(tessStyle.height)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> </span><span class="ace_string ace_strong">**Day 5 DOM Event**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_text ace_xml">file index.html</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;!DOCTYPE html&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;html lang="en"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;head&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;meta charset="UTF-8"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;title&gt;Document&lt;/title&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;script src="script.js"&gt;&lt;/script&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;/head&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;body&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    //cara 1 memberikan event</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;h1 onclick="alert('selamat datang')"&gt;Hallo&lt;/h1&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;p id="paragraf"&gt;click me&lt;/p&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;button id="btn"&gt;klik saya&lt;/button&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;/body&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;/html&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**file script.js**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let paragraf = document.getElementById("paragraf")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">//cara ke - 2</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">paragraf.onclick = function (){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    alert("ini dari paragraf ")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">}</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">// paragraf.onclick = tampilkanAlert</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">paragraf.onclick = function(){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    confirm("apakah ini dari paragraf?")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">}</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">function tampilkanAlert(){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    alert("ini alert")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">}</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">//cara ke 3</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let button = document.getElementById("btn")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">button.addEventListener("click", function(event){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log(event.target)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    alert("ini dari button")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">})</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">// // button.addEventListener("click", tampilkanAlert)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">// button.addEventListener("click", function(){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">//     confirm("apakah dari button?")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">// })</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**file  counter.html**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;!DOCTYPE html&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;html lang="en"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;head&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;meta charset="UTF-8"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;title&gt;Document&lt;/title&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;script src="counter.js"&gt;&lt;/script&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;/head&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;body&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;div&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;button id="decrement"&gt;-&lt;/button&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;span id="counter"&gt;0&lt;/span&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;button id="increment"&gt;+&lt;/button&gt;    </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;/div&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;/body&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;/html&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**file counter.js**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let btnDecrement = document.getElementById("decrement")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let btnIncrement = document.getElementById("increment")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let counter = document.getElementById("counter")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let angka = 0</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">btnIncrement.addEventListener("click", function(){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    angka = angka + 1</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    counter.innerText = angka</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    // console.log(angka)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    // console.log("increment")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">})</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">btnDecrement.addEventListener("click",function(){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    // console.log("decrement");</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    angka--</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    counter.innerText = angka</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">})</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**file login.html**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;!DOCTYPE html&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;html lang="en"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;head&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;meta charset="UTF-8"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;title&gt;Document&lt;/title&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;script src="login.js"&gt;&lt;/script&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;/head&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;body&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;dicv class="container"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;form id="sign-in"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;h1&gt;Sign In&lt;/h1&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;div class="field"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;label for="username"&gt;Username&lt;/label&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;input type="text" id="username" name="username" / &gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;/div&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;div class="field"&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;label for="password"&gt;Password&lt;/label&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;input type="text" id="password" name="password" /&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;/div&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;button type="submmit"&gt;Login&lt;/button&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    &lt;/form&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    &lt;/dicv&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;/body&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">&lt;/html&gt;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_string ace_strong">**file login.js**</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let loginForm = document.querySelector("#sign-in")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let inputUsername = document.querySelector('#username')</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let inputPassword = document.querySelector('#password')</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">let user = {</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    username:"Rajib",</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    password:"123"</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">}</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">loginForm.addEventListener("submit", (event) =&gt; {</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    event.preventDefault()</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log(inputUsername.value)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log(inputPassword.value)</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let userLogin = {</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    username: inputUsername.value,</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    password: inputPassword.value</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    console.log(userLogin);</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    let login = userLogin.username == user.username &amp;&amp; userLogin.password == user.password;</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    if(userLogin.username == user.username &amp;&amp; userLogin.password == user.password){</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    console.log("selamat anda berhasil login")</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    } else {</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_indent-guide">    </span><span class="ace_support ace_function">    console.log("username dan password salah"); </span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    }</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    //membersihkan form</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    //cara 1</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    loginForm.reset()</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    // cara2</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    // inputUsername.value =""</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    // inputPassword.value = ""</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">    //console.log("ini dari form yg di submit");</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">})</span></div></div><div class="ace_line_group" style="height:28px"><div class="ace_line" style="height:28px"><span class="ace_support ace_function">```</span></div></div></div><div class="ace_layer ace_marker-layer"></div><div class="ace_layer ace_cursor-layer"><div class="ace_cursor" style="left: 18px; top: 10892px; width: 7px; height: 28px; opacity: 0;"></div></div></div></div><div class="ace_scrollbar ace_scrollbar-v" style="display: none; width: 22px; bottom: 0px;"><div class="ace_scrollbar-inner" style="width: 22px; height: 10948px;"></div></div><div class="ace_scrollbar ace_scrollbar-h" style="display: none; height: 22px; left: 54px; right: 0px;"><div class="ace_scrollbar-inner" style="height: 22px; width: 701px;"></div></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: hidden;"><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: visible;"></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font-style: inherit; font-variant: inherit; font-stretch: inherit; font-size: inherit; line-height: inherit; font-family: inherit; overflow: visible;">XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</div></div></div>
</div>
<div id="preview1" class="g-b g-b--t1of2 split split-preview" style="height: 484px;">
<div id="preview" class="preview-html" preview="" debounce="150"><h4 class="code-line" data-line-start="0" data-line-end="1"><a id="Nama__Muh_Faizal_Rajib_0"></a>Nama : Muh. Faizal Rajib</h4>
<h4 class="code-line" data-line-start="1" data-line-end="2"><a id="Learning_Track__FrontEnd_Develovment_1"></a>Learning Track : Front-End Develovment</h4>
<h4 class="code-line" data-line-start="2" data-line-end="3"><a id="Challeng_Patner__Serrum_Gudskul_2"></a>Challeng Patner : Serrum Gudskul</h4>
<h4 class="code-line" data-line-start="3" data-line-end="4"><a id="Kelompok__FE_25_3"></a>Kelompok : FE 25</h4>
<h4 class="code-line" data-line-start="4" data-line-end="5"><a id="Week_2_4"></a>Week 2</h4>
<p class="has-line-data" data-line-start="5" data-line-end="6">.</p>
<h4 class="code-line" data-line-start="7" data-line-end="8"><a id="Day_1_Looping_7"></a><strong>Day 1 Looping</strong></h4>
<p class="has-line-data" data-line-start="8" data-line-end="9">Looping Looping adalah sebuah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi berhenti/stop tercapai.</p>
<p class="has-line-data" data-line-start="10" data-line-end="13">Perulangan For Loop<br>
<strong>For Loop</strong> Merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita kembangkan. for loop memiliki aturan tersendiri dalam penulisannya.<br>
contohnya:</p>
<pre><code class="has-line-data" data-line-start="14" data-line-end="22">    for (let i = 1; i &lt;= 10 ; i++){
        if (i == 6) {
            console.log(i, "Yes Ketemu")
        } else {
            console.log(i); 
        }
    }
</code></pre>
<p class="has-line-data" data-line-start="23" data-line-end="26">Perulangan While<br>
<strong>Perulang While</strong> merupakan perulangan yang bersifat indefinite alias tidak pasti, atau bahkan tidak terbatas.<br>
Contohnya :</p>
<pre><code class="has-line-data" data-line-start="27" data-line-end="44">    let i = 1;
    let isKetemu = false

    while(!isKetemu){
        if(
            i % 2 == 0 &amp;&amp;
            i % 3 == 0 &amp;&amp;
            i % 4 == 0 &amp;&amp;
            i % 5 == 0 &amp;&amp;
            i % 6 == 0
        ){
            console.log(i);
            isKetemu = true
        }
        i++
    }
</code></pre>
<p class="has-line-data" data-line-start="45" data-line-end="48">Perulangan Do While<br>
<strong>Perulangan Do While</strong> melakukan perulangan dulu, kemudian memeriksa kondisinya atau sayaratnya.<br>
Contohnya :</p>
<pre><code class="has-line-data" data-line-start="49" data-line-end="63">    do{
        if(
            i % 2 == 0 &amp;&amp;
            i % 3 == 0 &amp;&amp;
            i % 4 == 0 &amp;&amp;
            i % 5 == 0 &amp;&amp;
            i % 6 == 0
        ){
            console.log(i);
            isKetemu = true
        }
        i++
    } while (!isKetemu)
</code></pre>
<p class="has-line-data" data-line-start="64" data-line-end="66"><strong>Function</strong><br>
Function adalah kode program yang dirancang untuk menyelesaikan sebuah tugas tertentu, dan merupakan bagian dari program utama. Ketika di sadur ke dalam bahasa indonesia, function ini di sebut juga sebagai fungsi. Ada beberapa penulisan function :</p>
<ol>
<li class="has-line-data" data-line-start="66" data-line-end="67">function classic</li>
</ol>
<pre><code class="has-line-data" data-line-start="68" data-line-end="72">    function myFuction (parameter) {
        //Perintah yang dijalankan
    } 
</code></pre>
<ol start="2">
<li class="has-line-data" data-line-start="73" data-line-end="74">Arrow function</li>
</ol>
<pre><code class="has-line-data" data-line-start="75" data-line-end="79">    let myFunction = () =&gt; {
        //kode yang dijalankan
    }
</code></pre>
<ol start="3">
<li class="has-line-data" data-line-start="80" data-line-end="81">function variable</li>
</ol>
<pre><code class="has-line-data" data-line-start="82" data-line-end="86">    let myFuction = function (){
        //kode yang akan dijalankan
    }
</code></pre>
<h4 class="code-line" data-line-start="87" data-line-end="88"><a id="Day_2_Type_Data_87"></a><strong>Day 2 Type Data</strong></h4>
<p class="has-line-data" data-line-start="88" data-line-end="90">Ada beberapa type data<br>
<strong>Primitive</strong></p>
<ol>
<li class="has-line-data" data-line-start="90" data-line-end="91">String</li>
<li class="has-line-data" data-line-start="91" data-line-end="92">Number</li>
<li class="has-line-data" data-line-start="92" data-line-end="94">Bolean</li>
</ol>
<p class="has-line-data" data-line-start="94" data-line-end="95"><strong>Non-Primitive</strong></p>
<ol>
<li class="has-line-data" data-line-start="95" data-line-end="96">Array</li>
<li class="has-line-data" data-line-start="96" data-line-end="97">Method</li>
</ol>
<p class="has-line-data" data-line-start="99" data-line-end="102"><strong>String</strong><br>
Nilai dari type data ini selalu dibungkus dengan tanda kutip 2 (“Nilai dari string”), jadi segala sesuatu yang bungkus oleh tanda kutip 2 ini akan di baca String walaupun itu angka.<br>
Penulisan String :</p>
<pre><code class="has-line-data" data-line-start="103" data-line-end="108">    let hewan = "Kancil";

    console.log("Ini adalah " + hewan);
    console.log(`Ini adalah ${hewan}`);
</code></pre>
<h4 class="code-line" data-line-start="109" data-line-end="110"><a id="Day_3_DOM_109"></a><strong>Day 3 DOM</strong></h4>
<p class="has-line-data" data-line-start="110" data-line-end="115">DOM (Document Object Model) adalah dokumen (HTML) yang dimodelkan dalam sebuah objek.<br>
DOM adalah jembatan supaya bahasa pemrograman dapat berinteraksi dengan dokumen HTML, dengan DOM, JS dapat memanipulasi HTML.<br>
DOM bukan merupakan bahasa JavaScript. Tapi merupakan web API untuk membuat website cara akses nya menggunakan JavaScript. DOM tidak bisa digunakan pada Server.<br>
<strong>Traversing</strong><br>
Kebawah:</p>
<ol>
<li class="has-line-data" data-line-start="115" data-line-end="116">getElementById</li>
<li class="has-line-data" data-line-start="116" data-line-end="117">getElementsByClassName</li>
<li class="has-line-data" data-line-start="117" data-line-end="118">getElementsByTagName</li>
<li class="has-line-data" data-line-start="118" data-line-end="119">querySelectoriFamily</li>
<li class="has-line-data" data-line-start="119" data-line-end="121">childern</li>
</ol>
<p class="has-line-data" data-line-start="121" data-line-end="122">Keatas:</p>
<ol>
<li class="has-line-data" data-line-start="122" data-line-end="123">parentElement</li>
<li class="has-line-data" data-line-start="123" data-line-end="125">closest()</li>
</ol>
<p class="has-line-data" data-line-start="125" data-line-end="126">kesamping</p>
<ol>
<li class="has-line-data" data-line-start="126" data-line-end="127">nextElementSibling</li>
<li class="has-line-data" data-line-start="127" data-line-end="129">previousElementSibling</li>
</ol>
<p class="has-line-data" data-line-start="129" data-line-end="130">HTML Collection</p>
<h4 class="code-line" data-line-start="131" data-line-end="132"><a id="Day_4_DOM_Manipulation_131"></a><strong>Day 4 DOM Manipulation</strong></h4>
<p class="has-line-data" data-line-start="132" data-line-end="134">DOM Manipulation berinteraksi dengan DOM API untuk mengubah/memodifikasi dokumen HTML yang akan dirender di browser web.<br>
contoh index.html :</p>
<pre><code class="has-line-data" data-line-start="135" data-line-end="161">    &lt;!DOCTYPE html&gt;
    &lt;html lang="en"&gt;
        &lt;head&gt;
            &lt;meta charset="UTF-8"&gt;
            &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;
            &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
            &lt;title&gt;Document&lt;/title&gt;
            &lt;style&gt;
            #tess{
                width: 100px;
                height: 20px;
                background-color: brown;
            }
    &lt;/style&gt;    
        &lt;/head&gt;
        &lt;body&gt;
            &lt;div id="tess"&gt;&lt;/div&gt;
            &lt;div id="app"&gt;&lt;/div&gt;
            &lt;div id="end"&gt;
                &lt;a href="google.com" class="link"&gt;Google&lt;/a&gt;
            &lt;/div&gt;

            &lt;script src="script.js"&gt;&lt;/script&gt;
        &lt;/body&gt;
    &lt;/html&gt;
</code></pre>
<p class="has-line-data" data-line-start="161" data-line-end="162">Contoh scrip.js:</p>
<pre><code class="has-line-data" data-line-start="163" data-line-end="206">    let app = document.getElementById("app")

    console.log(app)

    //tag htmlnya akan di baca sebagai perintah
    app.innerHTML = "&lt;h1&gt;Hallo&lt;/h1&gt;"  

    //walaupun itu element html akan tetap dibaca text
    // app.innerText = "&lt;h1&gt;Apa Kabar&lt;/h1&gt;" 

    let p = document.createElement("p")
    p.innerText = "Ini adalah paragraf";

    app.append(p)
    // console.log(p);

    let p2 = document.createElement("p")
    p2.innerText = "paragraf ke-2"
    app.appendChild(p2)

    //appendChild tidak bisa input data string
    app.append("menggunakan append")
    // app.appendChild("appendChild")

    let end = document.getElementById("end")
    //end.remove

    let link = document.getElementsByClassName("link")[0]

    console.log(link.attributes)
    console.log(link.getAttribute("href"));
    link.setAttribute("id","google")

    link.style.color ="black"
    link.style.border = "1px solid black"
    link.style.padding = "5px 20px"
    link.style.backgroundColor = "aqua"

    let tess = document.getElementById("tess")

    let tessStyle = getComputedStyle(tess)
    console.log(tessStyle.height)
</code></pre>
<h4 class="code-line" data-line-start="207" data-line-end="208"><a id="Day_5_DOM_Event_207"></a><strong>Day 5 DOM Event</strong></h4>
<p class="has-line-data" data-line-start="208" data-line-end="209">file index.html</p>
<pre><code class="has-line-data" data-line-start="210" data-line-end="230">&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
    &lt;title&gt;Document&lt;/title&gt;

    &lt;script src="script.js"&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
    //cara 1 memberikan event
    &lt;h1 onclick="alert('selamat datang')"&gt;Hallo&lt;/h1&gt;

    &lt;p id="paragraf"&gt;click me&lt;/p&gt;

    &lt;button id="btn"&gt;klik saya&lt;/button&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre>
<p class="has-line-data" data-line-start="230" data-line-end="231"><strong>file script.js</strong></p>
<pre><code class="has-line-data" data-line-start="232" data-line-end="261">let paragraf = document.getElementById("paragraf")

//cara ke - 2
paragraf.onclick = function (){
    alert("ini dari paragraf ")
}

// paragraf.onclick = tampilkanAlert

paragraf.onclick = function(){
    confirm("apakah ini dari paragraf?")
}

function tampilkanAlert(){
    alert("ini alert")
}

//cara ke 3
let button = document.getElementById("btn")
button.addEventListener("click", function(event){
    console.log(event.target)
    alert("ini dari button")
})
// // button.addEventListener("click", tampilkanAlert)

// button.addEventListener("click", function(){
//     confirm("apakah dari button?")
// })
</code></pre>
<p class="has-line-data" data-line-start="262" data-line-end="263"><strong>file  counter.html</strong></p>
<pre><code class="has-line-data" data-line-start="264" data-line-end="283">&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
    &lt;title&gt;Document&lt;/title&gt;

    &lt;script src="counter.js"&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;div&gt;
        &lt;button id="decrement"&gt;-&lt;/button&gt;
        &lt;span id="counter"&gt;0&lt;/span&gt;
        &lt;button id="increment"&gt;+&lt;/button&gt;    
    &lt;/div&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre>
<p class="has-line-data" data-line-start="284" data-line-end="285"><strong>file counter.js</strong></p>
<pre><code class="has-line-data" data-line-start="286" data-line-end="305">let btnDecrement = document.getElementById("decrement")
let btnIncrement = document.getElementById("increment")
let counter = document.getElementById("counter")

let angka = 0

btnIncrement.addEventListener("click", function(){
    angka = angka + 1
    counter.innerText = angka
    // console.log(angka)
    // console.log("increment")
})

btnDecrement.addEventListener("click",function(){
    // console.log("decrement");
    angka--
    counter.innerText = angka
})
</code></pre>
<p class="has-line-data" data-line-start="306" data-line-end="307"><strong>file login.html</strong></p>
<pre><code class="has-line-data" data-line-start="308" data-line-end="339">&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
    &lt;title&gt;Document&lt;/title&gt;

    &lt;script src="login.js"&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;dicv class="container"&gt;
        &lt;form id="sign-in"&gt;
            &lt;h1&gt;Sign In&lt;/h1&gt;

            &lt;div class="field"&gt;
                &lt;label for="username"&gt;Username&lt;/label&gt;
                &lt;input type="text" id="username" name="username" / &gt;
            &lt;/div&gt;

            &lt;div class="field"&gt;
                &lt;label for="password"&gt;Password&lt;/label&gt;
                &lt;input type="text" id="password" name="password" /&gt;
            &lt;/div&gt;

            &lt;button type="submmit"&gt;Login&lt;/button&gt;
        &lt;/form&gt;
    &lt;/dicv&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre>
<p class="has-line-data" data-line-start="340" data-line-end="341"><strong>file login.js</strong></p>
<pre><code class="has-line-data" data-line-start="342" data-line-end="382">let loginForm = document.querySelector("#sign-in")
let inputUsername = document.querySelector('#username')
let inputPassword = document.querySelector('#password')

let user = {
    username:"Rajib",
    password:"123"
}

loginForm.addEventListener("submit", (event) =&gt; {
    event.preventDefault()
    console.log(inputUsername.value)
    console.log(inputPassword.value)

    let userLogin = {
        username: inputUsername.value,
        password: inputPassword.value
    }

    console.log(userLogin);

    let login = userLogin.username == user.username &amp;&amp; userLogin.password == user.password;


    if(userLogin.username == user.username &amp;&amp; userLogin.password == user.password){
        console.log("selamat anda berhasil login")
    } else {
        console.log("username dan password salah"); 
    }
    //membersihkan form
    //cara 1
    loginForm.reset()

    // cara2
    // inputUsername.value =""
    // inputPassword.value = ""

    //console.log("ini dari form yg di submit");
})
</code></pre>
</div>
</div>
</div>
</div>
</div>
<script src="https://m.servedby-buysellads.com/monetization.js" type="text/javascript"></script>
<script>
  (function () {
    if (typeof _bsa !== 'undefined' && _bsa) {
      _bsa.init('default', 'CVADP53W', 'placement:dillingerio', {
        target: '.ad-container',
        align: 'horizontal',
        disable_css: 'true'
      });
    }
  })();
</script>
<script src="./Week2_files/main.bundle.js.download" type="text/javascript" async=""></script>


</body></html>