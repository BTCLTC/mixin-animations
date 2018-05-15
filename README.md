# mixin-animation

        定義常用CSS3動畫效果的@mixin庫，支持Less和SASS兩種語法。

        @import 'mixin-animation/sass/fadein'; // 淡入效果（僅以SASS爲例）

        .fadein {
                @include fadein(1s); // 動畫時間默認值：1秒
        }

        如：fadeinT，fadeinR，fadeinB和fadeinL分別表示從上，右，下和左淡入效果
        特別說明：基於最小化原則，我們推薦按需加載相應的動畫效果
