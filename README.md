**@PoopooumgoodTTV**
CSS AND SETINGS of 3/25/24
[Css](/* ==UserStyle==
@name           kirka.io - Jun 2024
@namespace      github.com/openstyles/stylus
@version        1.0.0
@description    A new userstyle
@author         @PoopooumgoodTTV
==/UserStyle== */

@-moz-document domain("kikrka.io")
    {}
  /* @PoopooumgoodTTV  */
:root {
    --asscentColor: #ee0944;
    ;
}

::-webkit-scrollbar-thumb {
    background-color: var(--asscentColor);
}
::-webkit-scrollbar:horizontal {
    background-color: transparent !important;
}
::-webkit-scrollbar-thumb:horizontal {
    background: transparent !important;
    border-radius: 10px;
}

@keyframes glow {
    from {
        text-shadow: 0 0 5px #01f, 0 0 5px var(--asscentColor), 0 0 5px var(--asscentColor), 0 0 5px var(--asscentColor), 0 0 6px var(--asscentColor), 0 0 7px var(--asscentColor), 0 0 8px var(--asscentColor);
    }
}

/* Glows Clan Name */
.clan-tag {
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

.promo-link-btn {
    display: none !important;
}
.soc-group[data-v-3c44abf2] {
    display: none;
}


/* Removed Live steam */
.live-streams {
    opacity: 0;
    transition-duration: 1s;
}

.live-streams:hover {
    opacity: 1;
}
/* Transparent */
.box,
.input,
.quests,
.quest,
.tip,
.amount,
.reward,
.progress-line {
    background: transparent !important;
    border: none !important;
}

.active {
    border-bottom: var(--asscentColor) solid 0.125rem !important;
}

/* Text Color */
.level-value,
.levels,
.clan-tag,
.top-name,
.list-labels,
.active,
.level,
.header,
.lvl-leader,
.label-primary,
.awards-span,
.champions-league,
.champions-scores,
.all-scores-label,
.stat-name,
.progress-level-value {
    color: var(--asscentColor) !important;
}
.tab:hover,
.nav:hover {
    color: var(--asscentColor) !important;
}

/* Removes Logo  */
.interface .logo {
    width: auto;
    content: url("") !important;
    position: absolute;
    left: 43.5%;
    top: -3%;
    z-index: 9;
    transform-origin: top left;
}

/* Custom Backgorund */
#app > div.interface.text-2 > div.background {
    background-image: url("https://64.media.tumblr.com/24781a5ef4c6fc6ce7dcc7c2f1d0f458/e2469550566e930b-4c/s500x750/90f17002e930d7fef67cfebe4e9655fe6d2b53a1.pnj") !important;
    background-size: cover !important;
}
#app > div.interface.text-2 > div.background > div.pattern-bg,
#app > div.interface.text-2 > div.background > div.bg-radial {
    display: none !important
}

/* Money */
.moneys {
    flex-direction: column !important;
    position: absolute;
    left: 45%;
    top: 15%;
    z-index: 9;
    transform-origin: top left;
}

/* Socials */
.right-interface[data-v-6ef47e92] {
    position: absolute;
    left: 95%;
    top: 4%;
    z-index: 9;
    transform-origin: top left;
}
.soc-group {
    display: none !important;
}

.settings {
    background: transparent !important;
    border: none !important;
    padding-top: 20px !important;
    padding-right: 20px !important;
}

/* Left Menu */
.left-icons,
.icon-btn {
    background: transparent !important;
    border: none !important;
}

.text-icon {
    display: none !important;
}

.left-icons .icon-btn:hover {
    border-top: transparent !important;
}

/* Menu Icons */
.svg-icon--news,
.svg-icon--cube-edit,
.svg-icon--gamepad,
.svg-icon--store,
.svg-icon--castle2 {
    display: none;
}

/* Removed Profile Card */
.avatar-info,
.progress-label {
    display: none !important;
}

.user-info {
    padding-left: 3vw !important;
}

.progress {
    background: var(--asscentColor) !important;
    display: block !important;
}
.progress {
    box-shadow: 0px 0px 20px 6px var(--asscentColor);
}

.left-interface[data-v-6ef47e92] {
    position: absolute;
    left: 1%;
    top: 3%;
    z-index: 9;
    transform-origin: top left;
}

/* Profile */
div.card-cont.avatar-info,
div.card-cont.user-info,
.money {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.settings[data-v-e0ea0f78] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.card-cont[data-v-1cbd79ff] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.card-cont[data-v-1cbd79ff]:hover {
    background: transparent !important;
}


/* Inv & Friends */
#right-icons [data-v-ae524044] {
    height: 3.2rem;
}
#right-icons > div.icon-btn.text-1 {
    width: 139px;
    font-size: 18px;
    height: 65px;
}
#right-icons [data-v-1cbd79ff] {
    width: 139px;
    font-size: 18px;
    height: 65px;
}
#right-icons [data-v-b8de1e14] {
    display: none;
}
.right-icons .gun-img {
    display: none;
}
.right-icons .icon-btn {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}

/* Server & Play */
.select-mod,
.select-region {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
}
.select-regions-cont[data-v-6ef47e92] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
}
.join-using-link {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
}

#play-btn {
    background: rgba(68, 68, 68, 0) !important;
    box-shadow: 4px 4px 10px #0000 !important;
}

#play-btn .border-top,
#play-btn .border-bottom {
    background: none;
}

.triangle[data-v-02c36fca] {
    display: none !important;
}

/*	Ad Removal */
#ad-bottom,
#ad-left {
    visibility: hidden;
}
.className {
    display: none !important;
}
/* Mode Selection */
.select-mods-cont,
.select-mods-cont > hr {
    background: transparent!important;
    border: none !important;
}
.custom-checkbox > input:checked + span[data-v-47e1b746]:before {
    background-color: var(--asscentColor);
    border-color: var(--asscentColor);
}
.soc-group[data-v-f6928a74],
.text-soc[data-v-26102dd2] {
    display: none !important;
}

/* Check Box */
.private-btn > span[data-v-47e1b746] {
    content: url(https://64.media.tumblr.com/d458ca70c5231b1785b59699e668c597/d9076d87543a4b20-9c/s400x600/d6c7710d002b98064eb877e71ef9bec501ce9946.webp);
    position: fixed;
    left: 25px;
    width: 40px;
}

.private-btn > input:checked + span[data-v-47e1b746] {
    content: url(https://64.media.tumblr.com/d458ca70c5231b1785b59699e668c597/9286cda6fe3ab9b5-68/s400x600/44a00b49c294fc86fbcd4555d107e8be7e8c6462.webp);
}

.custom-checkbox > span[data-v-47e1b746]:before {
    border-radius: 50px;
    background-color: white;
    border: none;
}

.custom-checkbox > input:checked + span[data-v-47e1b746]:before {
    background-color: #f00;
}
/* Kill Sign */
#app > div.game-interface > div.ach-cont > div.achive-cont > svg > path,
#app > div.game-interface > div.desktop-game-interface > div.kill-bar-cont > div > svg {
    fill: var(--asscentColor) !important
}

/* chat */
.desktop-game-interface #WMNn {
    transform: scale(0);
    transition-duration: 0.25s !important;
}

.desktop-game-interface #WMNn:focus {
    transform: scale(1);
}
.clans,
.hub-container,
.mobile-fullscreen,
.add-friends,
.tab-bar,
.top-items,
.subject,
.inventory .avatar,
.inventory .bottom {
    background: transparent !important;
}

.head-text,
.reset-time,
.info-awards,
.news,
.list-cont,
.card-profile,
.profile .k-d,
.profile .statistics,
.profile-cont .progress[data-v-d2be3bc6] {
    background: transparent !important;
    box-shadow: none !important;
}

.tabs {
    background: transparent !important;
    border-bottom: none !important;
    box-shadow: none !important;
    border-right: none !important;
}

.active-tab,
.tab {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}

.limit {
    border-left: none !important;
}

.top-bar,
.home,
.name-page {
    display: none !important;
}

.container {
    background: transparent !important;
    backdrop-filter: blur(5px);
    box-shadow: none !important;
}

.champions-list {
    box-shadow: none !important;
}

.subjects,
.gun {
    background: transparent !important;
    border: none !important;
}

.profile .you {
    visibility: hidden;
}
.top[data-v-319b95e8] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.item[data-v-319b95e8] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.champions-list[data-v-3ade8f70] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.items .item[data-v-3ade8f70] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.card-head[data-v-5b2dc87c] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.list-container[data-v-3bcb580a] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.card-cont[data-v-040b7087] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.description[data-v-040b7087] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.all-scores[data-v-040b7087] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.champions-stat[data-v-040b7087] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.item-content[data-v-3bcb580a] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.server[data-v-679cb6a8] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.player[data-v-68ad001e] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.right-container[data-v-68ad001e] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.crosshair-static {
    visibility: visible !important;
    position: absolute;
    display: flex !important;
}
.messages[data-v-76a3fe0a] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.input[data-v-29d4a917] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.timer[data-v-1d4749de] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.bg[data-v-1d4749de] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.kill-bar-cont[data-v-e06e1414] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.head[data-v-a204db68] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.list[data-v-a204db68] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}

.name[data-v-2bbf437a] {
    padding-top: 20px;
}


.info-key-cont,
.list-weapons,
.mWwn,
.instruction {
    display: none !important;
}

.hp {
    margin-right: 20%;
}

.hp-progress {
    background-color: #f00 !important;
}

.state {
    position: fixed;
    width: 300px;
    top: 93%;
    left: 37% !important;
}

.cont-endurance {
    margin-left: 1.5%;
}
.endurance-progress {
    background-color: var(--asscentColor) !important;
}

.weapons-cont {
    position: fixed;
    width: 300px;
    top: 95%;
    left: 5%;
    margin-top: -100px;
    margin-left: 252px;
}

.ammunition {
    display: inline-block;
    position: fixed;
    left: calc(38% + 188px);
    top: calc(85%)
}

.bg[data-v-14e97ff8] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}

.hit {
    content: url(https://64.media.tumblr.com/7c8aa35da74e949ee7ecb0683a1f4651/2419f703ae1a384a-2f/s75x75_c1/c2d10f7873a2e527235f0be85b5b906e59a2da41.webp);
    margin-left: 4px;
    margin-top: 3px;
}
.player[data-v-3a61646a] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.timer[data-v-14e97ff8] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
/* kill icon */
.animate-cont {
    content: url(https://wallpapercave.com/uwp/uwp4428729.webp
);
    height: 100px;
    text-align: center;
    display: inline-block; 
   
})[Setings]({"MOBILE___SETTING":{"ALL_OPACITY___SETTING":1,"AIM_WHEN_FIRE___SETTING":1,"JOYSTICK_X___SETTING":0,"JOYSTICK_Y___SETTING":0,"JOYSTICK_SCALE___SETTING":1,"JOYSTICK_OPACITY___SETTING":0.5,"FIRE_LEFT_X___SETTING":0,"FIRE_LEFT_Y___SETTING":0,"FIRE_LEFT_SCALE___SETTING":1,"FIRE_LEFT_OPACITY___SETTING":0.75,"FIRE_RIGHT_X___SETTING":0,"FIRE_RIGHT_Y___SETTING":0,"FIRE_RIGHT_SCALE___SETTING":1,"FIRE_RIGHT_OPACITY___SETTING":0.4,"AIM_X___SETTING":0,"AIM_Y___SETTING":0,"AIM_SCALE___SETTING":1,"AIM_OPACITY___SETTING":0.35,"RELOAD_X___SETTING":0,"RELOAD_Y___SETTING":0,"RELOAD_SCALE___SETTING":1,"RELOAD_OPACITY___SETTING":0.5,"JUMP_X___SETTING":0,"JUMP_Y___SETTING":0,"JUMP_SCALE___SETTING":1,"JUMP_OPACITY___SETTING":0.5,"SIT_X___SETTING":0,"SIT_Y___SETTING":0,"SIT_SCALE___SETTING":1,"SIT_OPACITY___SETTING":0.5,"DASH_X___SETTING":0,"DASH_Y___SETTING":0,"DASH_SCALE___SETTING":1,"DASH_OPACITY___SETTING":0.5,"MOUSE_AND_KEYBOARD___SETTING":0},"PRIVACY___SETTING":{"ANONYMOUS_MODE___SETTING":0},"GENERAL___SETTING":{"AUTOCLOSE_WINDOWS___SETTING":false},"CROSSHAIR___SETTING":{"DISPLAY_TYPE___SETTING":"static","STATIC_URL___SETTING":"https://64.media.tumblr.com/7c8aa35da74e949ee7ecb0683a1f4651/2419f703ae1a384a-2f/s75x75_c1/c2d10f7873a2e527235f0be85b5b906e59a2da41.webp"},"MATCHMAKING___SETTING":{"LOGGED_ONLY___SETTING":0,"MINUTES_LEFT___SETTING":1,"WARMUP_ONLY___SETTING":1},"MOUSE___SETTING":{"RAW_INPUT___SETTING":0,"SENSITIVITY___SETTING":50,"AIM_SENSITIVITY___SETTING":30,"FLICK_PROTECTION___SETTING":0,"FLICK_PROTECTION_X___SETTING":130,"FLICK_PROTECTION_Y___SETTING":110},"GRAPHICS___SETTING":{"MAIN_RESOLUTION___SETTING":1,"RENDER_SHADOWS___SETTING":0,"BRIGHTNESS___SETTING":"2","CONTRAST___SETTING":1,"AO_BRIGHTNESS___SETTING":1},"SOUND___SETTING":{"VOLUME_MAIN___SETTING":1,"VOLUME_AMBIENT___SETTING":1,"VOLUME_ACTION___SETTING":1,"VOLUME_ACHIEVEMENT___SETTING":1,"VOLUME_UI___SETTING":1},"EFFECTS___SETTING":{"RENDER_CASES___SETTING":1,"RENDER_BULLETS___SETTING":1,"RENDER_SMOKE___SETTING":1,"RENDER_DECALS___SETTING":1},"CAMERA___SETTING":{"MAIN_FOV___SETTING":"150","WEAPON_FOV___SETTING":"150","HIDE_ARMS___SETTING":"show","HIDE_ON_ADS___SETTING":0,"CROSSHAIR_ON_HIDE___SETTING":1},"KEYBINDINGS___SETTING":{"MOVE_FORWARD___SETTING":"KEY_W___KEY","MOVE_BACKWARD___SETTING":"KEY_S___KEY","MOVE_LEFT___SETTING":"KEY_A___KEY","MOVE_RIGHT___SETTING":"KEY_D___KEY","MOVE_FORWARD2___SETTING":"KEY_UP_ARROW___KEY","MOVE_BACKWARD2___SETTING":"KEY_DOWN_ARROW___KEY","MOVE_LEFT2___SETTING":"KEY_LEFT_ARROW___KEY","MOVE_RIGHT2___SETTING":"KEY_RIGHT_ARROW___KEY","MOVE_UP___SETTING":"KEY_SPACE___KEY","MOVE_DOWN___SETTING":"KEY_SHIFT___KEY","MOVE_DASH___SETTING":"KEY_E___KEY","RELOAD_WEAPON___SETTING":"KEY_R___KEY","AIM_WEAPON___SETTING":"KEY_X___KEY","SHOOT_WEAPON___SETTING":"KEY_F___KEY","INSPECT_WEAPON___SETTING":"KEY_W___KEY","FIRST_WEAPON___SETTING":"KEY_1___KEY","SECOND_WEAPON___SETTING":"KEY_2___KEY","THIRD_WEAPON___SETTING":"KEY_3___KEY","PREVIOUS_WEAPON___SETTING":"KEY_Q___KEY","TOGGLE_SCORES___SETTING":"KEY_TAB___KEY","TOGGLE_CHAT___SETTING":"KEY_ENTER___KEY","TOGGLE_INFO___SETTING":"KEY_I___KEY","RESET_STATE___SETTING":"KEY_R___KEY","CHECKPOINT___SETTING":"KEY_Q___KEY","SPECTATOR_FLY___SETTING":"KEY_F___KEY","SPECTATOR_FPS___SETTING":"KEY_G___KEY","SPECTATOR_TPS___SETTING":"KEY_H___KEY","SPECTATOR_NEXT___SETTING":"MOUSE_LEFT___KEY","SPECTATOR_PREVIOUS___SETTING":"MOUSE_RIGHT___KEY","SPECTATOR_WALLS___SETTING":"KEY_X___KEY","TOGGLE_MENU___SETTING":"KEY_P___KEY"},"ANIMATIONS___SETTING":{"PULL_POS_Y___SETTING":0.5,"PULL_POS_Y_SPEED___SETTING":1,"PULL_POS_Y_SPEED_REVERSE___SETTING":1,"PULL_POS_Z___SETTING":0.5,"PULL_POS_Z_SPEED___SETTING":1,"PULL_POS_Z_SPEED_REVERSE___SETTING":1},"PLAYERS___SETTING":{"HP_BAR___SETTING":1,"RENDER_COLOR___SETTING":"#ff0000","RENDER_TEXTURE___SETTING":0,"RENDER_WEAPON___SETTING":0,"PLAY_ANIMATIONS___SETTING":0},"SNIPER___SETTING":{"SCOPE_URL___SETTING":"https://64.media.tumblr.com/7c8aa35da74e949ee7ecb0683a1f4651/2419f703ae1a384a-2f/s75x75_c1/c2d10f7873a2e527235f0be85b5b906e59a2da41.webp"},"BLOCKS___SETTING":{"RENDER_TEXTURE___SETTING":1,"BAKE_AO___SETTING":1,"RENDER_COLOR___SETTING":"#ffffff","TEXTURE_URL___SETTING":"https://64.media.tumblr.com/7cb0ada70aff5a9a48cbe55fa0c85050/e33e55c2eda023c6-47/s400x600/e27c0c41f30db21dfe481c22b28a70b14b449040.webp","DANCING___SETTING":0,"RGB_EFFECT___SETTING":0,"RGB_EFFECT_SPEED___SETTING":0.5,"RGB_EFFECT_AMPLITUDE___SETTING":0.5,"RGB_EFFECT_BRIGHTNESS___SETTING":1,"RGB_EFFECT_RED___SETTING":1,"RGB_EFFECT_GREEN___SETTING":1,"RGB_EFFECT_BLUE___SETTING":1,"RGB_EFFECT_RED_OFFSET___SETTING":0,"RGB_EFFECT_GREEN_OFFSET___SETTING":2,"RGB_EFFECT_BLUE_OFFSET___SETTING":4},"SKYBOX___SETTING":{"RENDER_TEXTURE___SETTING":1,"RENDER_COLOR___SETTING":"#ffffff","TEXTURE_IMG1___SETTING":"https://64.media.tumblr.com/8c1eb2a0235551fdebee127c9d62d32e/5ab4c6357fb13db5-9a/s540x810/222c8f9e9af31dad57cb26d83c35df4105fdfc7c.webp","TEXTURE_IMG2___SETTING":"https://64.media.tumblr.com/8c1eb2a0235551fdebee127c9d62d32e/5ab4c6357fb13db5-9a/s540x810/222c8f9e9af31dad57cb26d83c35df4105fdfc7c.webp","TEXTURE_IMG3___SETTING":"https://64.media.tumblr.com/8c1eb2a0235551fdebee127c9d62d32e/5ab4c6357fb13db5-9a/s540x810/222c8f9e9af31dad57cb26d83c35df4105fdfc7c.webp","TEXTURE_IMG4___SETTING":"https://64.media.tumblr.com/8c1eb2a0235551fdebee127c9d62d32e/5ab4c6357fb13db5-9a/s540x810/222c8f9e9af31dad57cb26d83c35df4105fdfc7c.webp","TEXTURE_IMG5___SETTING":"https://64.media.tumblr.com/8c1eb2a0235551fdebee127c9d62d32e/5ab4c6357fb13db5-9a/s540x810/222c8f9e9af31dad57cb26d83c35df4105fdfc7c.webphttps://64.media.tumblr.com/8c1eb2a0235551fdebee127c9d62d32e/5ab4c6357fb13db5-9a/s540x810/222c8f9e9af31dad57cb26d83c35df4105fdfc7c.webp","TEXTURE_IMG6___SETTING":"https://64.media.tumblr.com/8c1eb2a0235551fdebee127c9d62d32e/5ab4c6357fb13db5-9a/s540x810/222c8f9e9af31dad57cb26d83c35df4105fdfc7c.webp"}})
