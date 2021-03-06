# Bulma Stylus [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/) [![Gitter Chat](https://badges.gitter.im/frapsoft/frapsoft.svg)](https://gitter.im/frapsoft/frapsoft/)  

**Stylus Version of the current Bulma Repository (Version 0.1.2)**

- Bulma Version: 0.1.2
- GitHub Repository: <https://github.com/jgthms/bulma>
- Website: <http://bulma.io/>
    

**bulma.styl:**

```
html, body, body div, span, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, abbr, address, cite, code, del, dfn, em, img, ins, kbd, q, samp, small, strong, sub, sup, var, b, i, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, figure, footer, header, menu, nav, section, time, mark, audio, video, details, summary
  margin 0
  padding 0
  border 0
  font-size 100%
  font-weight normal
  vertical-align baseline
  background transparent

article, aside, figure, footer, header, nav, section, details, summary
  display block

html
  box-sizing border-box
  overflow-y scroll

*,
*:before,
*:after
  box-sizing inherit

img,
object,
embed
  max-width 100%

ul
  list-style none

blockquote, q
  quotes none

blockquote:before,
blockquote:after,
q:before,
q:after
  content ''
  content none

a
  margin 0
  padding 0
  font-size 100%
  vertical-align baseline
  background transparent
  color #1fc8db
  cursor pointer
  text-decoration none
  -webkit-transition none 86ms ease-out
  transition none 86ms ease-out
  &:hover
    color #222324
  &.box
    &:active
      box-shadow inset 0 1px 2px rgba(17, 17, 17, 0.2), 0 0 0 1px #1fc8db
  &.panel-block
    &:hover
      background-color #f5f7fa

del
  text-decoration line-through

abbr[title], dfn[title]
  border-bottom 1px dotted #000
  cursor help

table
  border-collapse collapse
  border-spacing 0
  font-size inherit
  font 100%
  width 100%
  th
    color #222324

th
  font-weight bold
  vertical-align bottom

td
  font-weight normal
  vertical-align top

hr
  display block
  height 1px
  border 0
  border-top 1px solid #ccc
  margin 1em 0
  padding 0
  border-top-color #d3d6db
  margin 40px 0

input, select
  vertical-align middle

pre
  white-space pre
  white-space pre-wrap
  white-space pre-line
  word-wrap break-word
  background-color #f5f7fa
  color #69707a
  white-space pre
  word-wrap normal
  code
    background-color #f5f7fa
    color #69707a
    display block
    overflow-x auto
    padding 16px 20px

input[type="radio"]
  vertical-align text-bottom

input[type="checkbox"]
  vertical-align bottom

select, input, textarea
  font 99% sans-serif

small
  font-size 85%
  font-size 11px

strong
  font-weight bold
  color #222324
  font-weight 700

td, td img
  vertical-align top

sub, sup
  font-size 75%
  line-height 0
  position relative

sup
  top -0.5em

sub
  bottom -0.25em

pre, code, kbd, samp
  font-family monospace, sans-serif

label,
input[type=button],
input[type=submit],
input[type=file],
button
  cursor pointer

button, input, select, textarea
  margin 0

button,
input[type=button]
  width auto
  overflow visible

@-webkit-keyframes
  spin-around
    from {
    -webkit-transform rotate(0deg)
    transform rotate(0deg)

to
  -webkit-transform rotate(359deg)
  transform rotate(359deg)
  -webkit-transform rotate(359deg)
  transform rotate(359deg)

}
  @keyframes
    spin-around
      from {
    -webkit-transform rotate(0deg)
      transform rotate(0deg)
  html
    background-color #f5f7fa
    font-size 14px
    -moz-osx-font-smoothing grayscale
    -webkit-font-smoothing antialiased
    min-width 300px
    overflow-x hidden
    overflow-y scroll
    text-rendering optimizeLegibility

article,
aside,
figure,
footer,
header,
hgroup,
section
  display block

body,
button,
input,
select,
textarea
  font-family "Helvetica Neue", "Helvetica", "Arial", sans-serif

code,
pre
  -moz-osx-font-smoothing auto
  -webkit-font-smoothing auto
  font-family "Source Code Pro", "Monaco", "Inconsolata", monospace
  line-height 1.25

body
  color #69707a
  font-size 1rem
  font-weight 400
  line-height 1.428571428571429

code
  background-color #f5f7fa
  color #ed6c63
  font-size 12px
  font-weight normal
  padding 1px 2px 2px

img
  max-width 100%

input[type="checkbox"],
input[type="radio"]
  vertical-align baseline

span
  font-style inherit
  font-weight inherit

table td,
table th
  text-align left
  vertical-align top

.block:not(:last-child), .box:not(:last-child), .content:not(:last-child), .notification:not(:last-child), .progress:not(:last-child), .title:not(:last-child),
.subtitle:not(:last-child), .highlight:not(:last-child), .level:not(:last-child), .message:not(:last-child), .tabs:not(:last-child)
  margin-bottom 20px

.container
  position relative
  & > .nav
    & > .nav-left
      & > .nav-item
        &:first-child
          &:not(.is-tab)
            padding-left 0
    & > .nav-right
      & > .nav-item
        &:last-child
          &:not(.is-tab)
            padding-right 0

@media screen and (min-width: 980px)
  .container
    margin 0 auto
    max-width 960px
    &.is-fluid
      margin 0 20px
      max-width none

@media screen and (min-width: 1180px)
  .container
    max-width 1200px

.fa
  font-size 21px
  text-align center
  vertical-align top

.is-block
  display block

@media screen and (max-width: 768px)
  .is-block-mobile
    display block !important

@media screen and (min-width: 769px)
  .is-block-tablet
    display block !important

@media screen and (min-width: 769px) and (max-width: 979px)
  .is-block-tablet-only
    display block !important

@media screen and (max-width: 979px)
  .is-block-touch
    display block !important

@media screen and (min-width: 980px)
  .is-block-desktop
    display block !important

@media screen and (min-width: 980px) and (max-width: 1179px)
  .is-block-desktop-only
    display block !important

@media screen and (min-width: 1180px)
  .is-block-widescreen
    display block !important

.is-flex
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex

@media screen and (max-width: 768px)
  .is-flex-mobile
    display -webkit-box !important
    display -webkit-flex !important
    display -ms-flexbox !important
    display flex !important

@media screen and (min-width: 769px)
  .is-flex-tablet
    display -webkit-box !important
    display -webkit-flex !important
    display -ms-flexbox !important
    display flex !important

@media screen and (min-width: 769px) and (max-width: 979px)
  .is-flex-tablet-only
    display -webkit-box !important
    display -webkit-flex !important
    display -ms-flexbox !important
    display flex !important

@media screen and (max-width: 979px)
  .is-flex-touch
    display -webkit-box !important
    display -webkit-flex !important
    display -ms-flexbox !important
    display flex !important

@media screen and (min-width: 980px)
  .is-flex-desktop
    display -webkit-box !important
    display -webkit-flex !important
    display -ms-flexbox !important
    display flex !important

@media screen and (min-width: 980px) and (max-width: 1179px)
  .is-flex-desktop-only
    display -webkit-box !important
    display -webkit-flex !important
    display -ms-flexbox !important
    display flex !important

@media screen and (min-width: 1180px)
  .is-flex-widescreen
    display -webkit-box !important
    display -webkit-flex !important
    display -ms-flexbox !important
    display flex !important

.is-inline
  display inline

@media screen and (max-width: 768px)
  .is-inline-mobile
    display inline !important

@media screen and (min-width: 769px)
  .is-inline-tablet
    display inline !important

@media screen and (min-width: 769px) and (max-width: 979px)
  .is-inline-tablet-only
    display inline !important

@media screen and (max-width: 979px)
  .is-inline-touch
    display inline !important

@media screen and (min-width: 980px)
  .is-inline-desktop
    display inline !important

@media screen and (min-width: 980px) and (max-width: 1179px)
  .is-inline-desktop-only
    display inline !important

@media screen and (min-width: 1180px)
  .is-inline-widescreen
    display inline !important

.is-inline-block
  display inline-block

@media screen and (max-width: 768px)
  .is-inline-block-mobile
    display inline-block !important

@media screen and (min-width: 769px)
  .is-inline-block-tablet
    display inline-block !important

@media screen and (min-width: 769px) and (max-width: 979px)
  .is-inline-block-tablet-only
    display inline-block !important

@media screen and (max-width: 979px)
  .is-inline-block-touch
    display inline-block !important

@media screen and (min-width: 980px)
  .is-inline-block-desktop
    display inline-block !important

@media screen and (min-width: 980px) and (max-width: 1179px)
  .is-inline-block-desktop-only
    display inline-block !important

@media screen and (min-width: 1180px)
  .is-inline-block-widescreen
    display inline-block !important

.is-inline-flex
  display -webkit-inline-box
  display -webkit-inline-flex
  display -ms-inline-flexbox
  display inline-flex

@media screen and (max-width: 768px)
  .is-inline-flex-mobile
    display -webkit-inline-box !important
    display -webkit-inline-flex !important
    display -ms-inline-flexbox !important
    display inline-flex !important

@media screen and (min-width: 769px)
  .is-inline-flex-tablet
    display -webkit-inline-box !important
    display -webkit-inline-flex !important
    display -ms-inline-flexbox !important
    display inline-flex !important

@media screen and (min-width: 769px) and (max-width: 979px)
  .is-inline-flex-tablet-only
    display -webkit-inline-box !important
    display -webkit-inline-flex !important
    display -ms-inline-flexbox !important
    display inline-flex !important

@media screen and (max-width: 979px)
  .is-inline-flex-touch
    display -webkit-inline-box !important
    display -webkit-inline-flex !important
    display -ms-inline-flexbox !important
    display inline-flex !important

@media screen and (min-width: 980px)
  .is-inline-flex-desktop
    display -webkit-inline-box !important
    display -webkit-inline-flex !important
    display -ms-inline-flexbox !important
    display inline-flex !important

@media screen and (min-width: 980px) and (max-width: 1179px)
  .is-inline-flex-desktop-only
    display -webkit-inline-box !important
    display -webkit-inline-flex !important
    display -ms-inline-flexbox !important
    display inline-flex !important

@media screen and (min-width: 1180px)
  .is-inline-flex-widescreen
    display -webkit-inline-box !important
    display -webkit-inline-flex !important
    display -ms-inline-flexbox !important
    display inline-flex !important

.is-clearfix
  &:after
    clear both
    content " "
    display table

.is-pulled-left
  float left

.is-pulled-right
  float right

.is-clipped
  overflow hidden !important

.is-overlay
  bottom 0
  left 0
  position absolute
  right 0
  top 0

.has-text-centered
  text-align center

.has-text-left
  text-align left

.has-text-right
  text-align right

.is-hidden
  display none !important

@media screen and (max-width: 768px)
  .is-hidden-mobile
    display none !important

@media screen and (min-width: 769px)
  .is-hidden-tablet
    display none !important

@media screen and (min-width: 769px) and (max-width: 979px)
  .is-hidden-tablet-only
    display none !important

@media screen and (max-width: 979px)
  .is-hidden-touch
    display none !important

@media screen and (min-width: 980px)
  .is-hidden-desktop
    display none !important

@media screen and (min-width: 980px) and (max-width: 1179px)
  .is-hidden-desktop-only
    display none !important

@media screen and (min-width: 1180px)
  .is-hidden-widescreen
    display none !important

.is-disabled
  pointer-events none

.is-marginless
  margin 0 !important

.box
  background-color #fff
  border-radius 5px
  box-shadow 0 2px 3px rgba(17, 17, 17, 0.1), 0 0 0 1px rgba(17, 17, 17, 0.1)
  display block
  padding 20px

a.box:hover, a.box:focus
  box-shadow 0 2px 3px rgba(17, 17, 17, 0.1), 0 0 0 1px #1fc8db

.button
  -moz-appearance none
  -webkit-appearance none
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  align-items center
  background-color white
  border 1px solid #d3d6db
  border-radius 3px
  color #222324
  display -webkit-inline-box
  display -webkit-inline-flex
  display -ms-inline-flexbox
  display inline-flex
  font-size 14px
  height 32px
  -webkit-box-pack start
  -webkit-justify-content flex-start
  -ms-flex-pack start
  justify-content flex-start
  line-height 24px
  padding-left 8px
  padding-right 8px
  position relative
  vertical-align top
  -webkit-box-pack center
  -webkit-justify-content center
  -ms-flex-pack center
  justify-content center
  padding-left 10px
  padding-right 10px
  text-align center
  white-space nowrap
  &:hover
    border-color #aeb1b5
  strong
    color inherit
  small
    display block
    font-size 11px
    line-height 1
    margin-top 5px
  &:active
    box-shadow inset 0 1px 2px rgba(17, 17, 17, 0.2)
  &.is-white
    background-color #fff
    border-color transparent
    color #111
    &:active
      border-color transparent
    &.is-inverted
      background-color #111
      color #fff
      &:hover
        background-color #040404
    &.is-loading
      &:after
        border-color transparent transparent #111 #111 !important
    &.is-outlined
      background-color transparent
      border-color #fff
      color #fff
  &.is-black
    background-color #111
    border-color transparent
    color #fff
    &:active
      border-color transparent
    &.is-inverted
      background-color #fff
      color #111
      &:hover
        background-color #f2f2f2
    &.is-loading
      &:after
        border-color transparent transparent #fff #fff !important
    &.is-outlined
      background-color transparent
      border-color #111
      color #111
  &.is-light
    background-color #f5f7fa
    border-color transparent
    color #69707a
    &:active
      border-color transparent
    &.is-inverted
      background-color #69707a
      color #f5f7fa
      &:hover
        background-color #5d636c
    &.is-loading
      &:after
        border-color transparent transparent #69707a #69707a !important
    &.is-outlined
      background-color transparent
      border-color #f5f7fa
      color #f5f7fa
  &.is-dark
    background-color #69707a
    border-color transparent
    color #f5f7fa
    &:active
      border-color transparent
    &.is-inverted
      background-color #f5f7fa
      color #69707a
      &:hover
        background-color #e4e9f2
    &.is-loading
      &:after
        border-color transparent transparent #f5f7fa #f5f7fa !important
    &.is-outlined
      background-color transparent
      border-color #69707a
      color #69707a
  &.is-primary
    background-color #1fc8db
    border-color transparent
    color white
    &:active
      border-color transparent
    &.is-inverted
      background-color white
      color #1fc8db
      &:hover
        background-color #f2f2f2
    &.is-loading
      &:after
        border-color transparent transparent white white !important
    &.is-outlined
      background-color transparent
      border-color #1fc8db
      color #1fc8db
  &.is-info
    background-color #42afe3
    border-color transparent
    color white
    &:active
      border-color transparent
    &.is-inverted
      background-color white
      color #42afe3
      &:hover
        background-color #f2f2f2
    &.is-loading
      &:after
        border-color transparent transparent white white !important
    &.is-outlined
      background-color transparent
      border-color #42afe3
      color #42afe3
  &.is-success
    background-color #97cd76
    border-color transparent
    color white
    &:active
      border-color transparent
    &.is-inverted
      background-color white
      color #97cd76
      &:hover
        background-color #f2f2f2
    &.is-loading
      &:after
        border-color transparent transparent white white !important
    &.is-outlined
      background-color transparent
      border-color #97cd76
      color #97cd76
  &.is-warning
    background-color #fce473
    border-color transparent
    color rgba(17, 17, 17, 0.5)
    &:active
      border-color transparent
    &.is-inverted
      background-color rgba(17, 17, 17, 0.5)
      color #fce473
      &:hover
        background-color rgba(4, 4, 4, 0.5)
    &.is-loading
      &:after
        border-color transparent transparent rgba(17, 17, 17, 0.5) rgba(17, 17, 17, 0.5) !important
    &.is-outlined
      background-color transparent
      border-color #fce473
      color #fce473
  &.is-danger
    background-color #ed6c63
    border-color transparent
    color white
    &:active
      border-color transparent
    &.is-inverted
      background-color white
      color #ed6c63
      &:hover
        background-color #f2f2f2
    &.is-loading
      &:after
        border-color transparent transparent white white !important
    &.is-outlined
      background-color transparent
      border-color #ed6c63
      color #ed6c63
  &.is-link
    background-color transparent
    border-color transparent
    color #69707a
    text-decoration underline
  &.is-small
    border-radius 2px
    font-size 11px
    height 24px
    line-height 16px
    padding-left 6px
    padding-right 6px
  &.is-medium
    font-size 18px
    height 40px
    padding-left 14px
    padding-right 14px
  &.is-large
    font-size 22px
    height 48px
    padding-left 20px
    padding-right 20px
  &.is-fullwidth
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    width 100%
  &.is-loading
    color transparent !important
    pointer-events none
    &:after
      left 50%
      margin-left -8px
      margin-top -8px
      position absolute
      top 50%
      position absolute !important

.button:active, .button:focus, .button.is-active
  border-color #1fc8db
  outline none

.button[disabled], .button.is-disabled
  background-color #f5f7fa
  border-color #d3d6db
  cursor not-allowed
  pointer-events none
  opacity 0.5

.button[disabled]::-moz-placeholder, .button.is-disabled::-moz-placeholder
  color rgba(34, 35, 36, 0.3)

.button[disabled]::-webkit-input-placeholder, .button.is-disabled::-webkit-input-placeholder
  color rgba(34, 35, 36, 0.3)

.button[disabled]:-moz-placeholder, .button.is-disabled:-moz-placeholder
  color rgba(34, 35, 36, 0.3)

.button[disabled]:-ms-input-placeholder, .button.is-disabled:-ms-input-placeholder
  color rgba(34, 35, 36, 0.3)

.button .icon:first-child,
.button .tag:first-child
  margin-left -2px
  margin-right 4px

.button .icon:last-child,
.button .tag:last-child
  margin-left 4px
  margin-right -2px

.button:hover, .button:focus, .button.is-active
  color #222324

.button.is-white:hover, .button.is-white:focus, .button.is-white.is-active
  background-color #e6e6e6
  border-color transparent
  color #111

.button.is-white.is-outlined:hover, .button.is-white.is-outlined:focus
  background-color #fff
  border-color #fff
  color #111

.button.is-black:hover, .button.is-black:focus, .button.is-black.is-active
  background-color black
  border-color transparent
  color #fff

.button.is-black.is-outlined:hover, .button.is-black.is-outlined:focus
  background-color #111
  border-color #111
  color #fff

.button.is-light:hover, .button.is-light:focus, .button.is-light.is-active
  background-color #d3dce9
  border-color transparent
  color #69707a

.button.is-light.is-outlined:hover, .button.is-light.is-outlined:focus
  background-color #f5f7fa
  border-color #f5f7fa
  color #69707a

.button.is-dark:hover, .button.is-dark:focus, .button.is-dark.is-active
  background-color #51575f
  border-color transparent
  color #f5f7fa

.button.is-dark.is-outlined:hover, .button.is-dark.is-outlined:focus
  background-color #69707a
  border-color #69707a
  color #f5f7fa

.button.is-primary:hover, .button.is-primary:focus, .button.is-primary.is-active
  background-color #199fae
  border-color transparent
  color white

.button.is-primary.is-outlined:hover, .button.is-primary.is-outlined:focus
  background-color #1fc8db
  border-color #1fc8db
  color white

.button.is-info:hover, .button.is-info:focus, .button.is-info.is-active
  background-color #1f99d3
  border-color transparent
  color white

.button.is-info.is-outlined:hover, .button.is-info.is-outlined:focus
  background-color #42afe3
  border-color #42afe3
  color white

.button.is-success:hover, .button.is-success:focus, .button.is-success.is-active
  background-color #7bbf51
  border-color transparent
  color white

.button.is-success.is-outlined:hover, .button.is-success.is-outlined:focus
  background-color #97cd76
  border-color #97cd76
  color white

.button.is-warning:hover, .button.is-warning:focus, .button.is-warning.is-active
  background-color #fbda41
  border-color transparent
  color rgba(17, 17, 17, 0.5)

.button.is-warning.is-outlined:hover, .button.is-warning.is-outlined:focus
  background-color #fce473
  border-color #fce473
  color rgba(17, 17, 17, 0.5)

.button.is-danger:hover, .button.is-danger:focus, .button.is-danger.is-active
  background-color #e84135
  border-color transparent
  color white

.button.is-danger.is-outlined:hover, .button.is-danger.is-outlined:focus
  background-color #ed6c63
  border-color #ed6c63
  color white

.button.is-link:hover, .button.is-link:focus
  background-color #d3d6db
  color #222324

.content
  a
    &:not(.button)
      border-bottom 1px solid #d3d6db
    &:not(.button):visited
      color #847bb9
    &:not(.button):hover
      border-bottom-color #1fc8db
  li
    & + li
      margin-top 0.25em
  blockquote
    background-color #f5f7fa
    border-left 5px solid #d3d6db
    padding 1.5em
  h1
    font-size 2em
  h2
    font-size 1.75em
  h3
    font-size 1.5em
  h4
    font-size 1.25em
  h5
    font-size 1.125em
  h6
    font-size 1em
  ol
    list-style decimal outside
    margin-left 2em
    margin-right 2em
    margin-top 1em
  ul
    list-style disc outside
    margin-left 2em
    margin-right 2em
    margin-top 1em
    ul
      list-style-type circle
      margin-top 0.5em
      ul
        list-style-type square
  &.is-medium
    font-size 18px
    code
      font-size 14px
  &.is-large
    font-size 24px
    code
      font-size 18px

.content blockquote:not(:last-child),
.content p:not(:last-child),
.content ol:not(:last-child),
.content ul:not(:last-child)
  margin-bottom 1em

.content h1,
.content h2,
.content h3,
.content h4,
.content h5,
.content h6
  color #222324
  font-weight 300
  line-height 1.125
  margin-bottom 20px

.content h1:not(:first-child),
.content h2:not(:first-child),
.content h3:not(:first-child)
  margin-top 40px

.input, .textarea
  -moz-appearance none
  -webkit-appearance none
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  align-items center
  background-color white
  border 1px solid #d3d6db
  border-radius 3px
  color #222324
  display -webkit-inline-box
  display -webkit-inline-flex
  display -ms-inline-flexbox
  display inline-flex
  font-size 14px
  height 32px
  -webkit-box-pack start
  -webkit-justify-content flex-start
  -ms-flex-pack start
  justify-content flex-start
  line-height 24px
  padding-left 8px
  padding-right 8px
  position relative
  vertical-align top
  box-shadow inset 0 1px 2px rgba(17, 17, 17, 0.1)
  max-width 100%
  width 100%

.input:hover, .textarea:hover
  border-color #aeb1b5

.input:active, .textarea:active, .input:focus, .textarea:focus, .input.is-active, .is-active.textarea
  border-color #1fc8db
  outline none

.input[disabled], [disabled].textarea, .input.is-disabled, .is-disabled.textarea
  background-color #f5f7fa
  border-color #d3d6db
  cursor not-allowed
  pointer-events none

.input[disabled]::-moz-placeholder, [disabled].textarea::-moz-placeholder, .input.is-disabled::-moz-placeholder, .is-disabled.textarea::-moz-placeholder
  color rgba(34, 35, 36, 0.3)

.input[disabled]::-webkit-input-placeholder, [disabled].textarea::-webkit-input-placeholder, .input.is-disabled::-webkit-input-placeholder, .is-disabled.textarea::-webkit-input-placeholder
  color rgba(34, 35, 36, 0.3)

.input[disabled]:-moz-placeholder, [disabled].textarea:-moz-placeholder, .input.is-disabled:-moz-placeholder, .is-disabled.textarea:-moz-placeholder
  color rgba(34, 35, 36, 0.3)

.input[disabled]:-ms-input-placeholder, [disabled].textarea:-ms-input-placeholder, .input.is-disabled:-ms-input-placeholder, .is-disabled.textarea:-ms-input-placeholder
  color rgba(34, 35, 36, 0.3)

.input.is-white, .is-white.textarea
  border-color #fff

.input.is-black, .is-black.textarea
  border-color #111

.input.is-light, .is-light.textarea
  border-color #f5f7fa

.input.is-dark, .is-dark.textarea
  border-color #69707a

.input.is-primary, .is-primary.textarea
  border-color #1fc8db

.input.is-info, .is-info.textarea
  border-color #42afe3

.input.is-success, .is-success.textarea
  border-color #97cd76

.input.is-warning, .is-warning.textarea
  border-color #fce473

.input.is-danger, .is-danger.textarea
  border-color #ed6c63

.input[type="search"], [type="search"].textarea
  border-radius 290486px

.input.is-small, .is-small.textarea
  border-radius 2px
  font-size 11px
  height 24px
  line-height 16px
  padding-left 6px
  padding-right 6px

.input.is-medium, .is-medium.textarea
  font-size 18px
  height 40px
  line-height 32px
  padding-left 10px
  padding-right 10px

.input.is-large, .is-large.textarea
  font-size 24px
  height 48px
  line-height 40px
  padding-left 12px
  padding-right 12px

.input.is-fullwidth, .is-fullwidth.textarea
  display block
  width 100%

.input.is-inline, .is-inline.textarea
  display inline
  width auto

.textarea
  display block
  line-height 1.2
  max-height 600px
  max-width 100%
  min-height 120px
  min-width 100%
  padding 10px
  resize vertical

.checkbox, .radio
  cursor pointer
  display inline-block
  line-height 16px
  position relative
  vertical-align top

.checkbox input, .radio input
  cursor pointer

.checkbox:hover, .radio:hover
  color #222324

.is-disabled.checkbox, .is-disabled.radio
  color #aeb1b5
  pointer-events none

.is-disabled.checkbox input, .is-disabled.radio input
  pointer-events none

.radio
  & + .radio
    margin-left 10px

.select
  display inline-block
  height 32px
  position relative
  vertical-align top
  select
    -moz-appearance none
    -webkit-appearance none
    -webkit-box-align center
    -webkit-align-items center
    -ms-flex-align center
    align-items center
    background-color white
    border 1px solid #d3d6db
    border-radius 3px
    color #222324
    display -webkit-inline-box
    display -webkit-inline-flex
    display -ms-inline-flexbox
    display inline-flex
    font-size 14px
    height 32px
    -webkit-box-pack start
    -webkit-justify-content flex-start
    -ms-flex-pack start
    justify-content flex-start
    line-height 24px
    padding-left 8px
    padding-right 8px
    position relative
    vertical-align top
    cursor pointer
    display block
    outline none
    padding-right 36px
    &:hover
      border-color #aeb1b5
      border-color #aeb1b5
    &.is-white
      border-color #fff
    &.is-black
      border-color #111
    &.is-light
      border-color #f5f7fa
    &.is-dark
      border-color #69707a
    &.is-primary
      border-color #1fc8db
    &.is-info
      border-color #42afe3
    &.is-success
      border-color #97cd76
    &.is-warning
      border-color #fce473
    &.is-danger
      border-color #ed6c63
    &::ms-expand
      display none
  &.is-fullwidth
    width 100%
    select
      width 100%
  &:after
    border 1px solid #1fc8db
    border-right 0
    border-top 0
    content " "
    display block
    height 7px
    pointer-events none
    position absolute
    -webkit-transform rotate(-45deg)
    transform rotate(-45deg)
    width 7px
    margin-top -6px
    right 16px
    top 50%
  &:hover
    &:after
      border-color #222324
  &.is-small
    height 24px
    select
      border-radius 2px
      font-size 11px
      height 24px
      line-height 16px
      padding-left 6px
      padding-right 6px
      padding-right 28px
  &.is-medium
    height 40px
    select
      font-size 18px
      height 40px
      line-height 32px
      padding-left 10px
      padding-right 10px
      padding-right 44px
  &.is-large
    height 48px
    select
      font-size 24px
      height 48px
      line-height 40px
      padding-left 12px
      padding-right 12px
      padding-right 52px

.select select:active, .select select:focus, .select select.is-active
  border-color #1fc8db
  outline none

.select select[disabled], .select select.is-disabled
  background-color #f5f7fa
  border-color #d3d6db
  cursor not-allowed
  pointer-events none

.select select[disabled]::-moz-placeholder, .select select.is-disabled::-moz-placeholder
  color rgba(34, 35, 36, 0.3)

.select select[disabled]::-webkit-input-placeholder, .select select.is-disabled::-webkit-input-placeholder
  color rgba(34, 35, 36, 0.3)

.select select[disabled]:-moz-placeholder, .select select.is-disabled:-moz-placeholder
  color rgba(34, 35, 36, 0.3)

.select select[disabled]:-ms-input-placeholder, .select select.is-disabled:-ms-input-placeholder
  color rgba(34, 35, 36, 0.3)

.label
  color #222324
  display block
  font-weight bold
  &:not(:last-child)
    margin-bottom 5px

.help
  display block
  font-size 11px
  margin-top 5px
  &.is-white
    color #fff
  &.is-black
    color #111
  &.is-light
    color #f5f7fa
  &.is-dark
    color #69707a
  &.is-primary
    color #1fc8db
  &.is-info
    color #42afe3
  &.is-success
    color #97cd76
  &.is-warning
    color #fce473
  &.is-danger
    color #ed6c63

@media screen and (max-width: 768px)
  .control-label
    margin-bottom 5px

@media screen and (min-width: 769px)
  .control-label
    -webkit-box-flex 1
    -webkit-flex-grow 1
    -ms-flex-positive 1
    flex-grow 1
    margin-right 20px
    padding-top 7px
    text-align right

.control
  position relative
  text-align left
  &:not(:last-child)
    margin-bottom 10px
  &.has-addons
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    -webkit-box-pack start
    -webkit-justify-content flex-start
    -ms-flex-pack start
    justify-content flex-start
    &.has-addons-centered
      -webkit-box-pack center
      -webkit-justify-content center
      -ms-flex-pack center
      justify-content center
    &.has-addons-right
      -webkit-box-pack end
      -webkit-justify-content flex-end
      -ms-flex-pack end
      justify-content flex-end
  &.has-icon
    & > .fa
      display inline-block
      font-size 14px
      height 24px
      line-height 24px
      text-align center
      vertical-align top
      width 24px
      color #aeb1b5
      pointer-events none
      position absolute
      top 4px
      z-index 4
    &:not(.has-icon-right)
      & > .fa
        left 4px
    &.has-icon-right
      & > .fa
        right 4px
  &.is-grouped
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    -webkit-box-pack start
    -webkit-justify-content flex-start
    -ms-flex-pack start
    justify-content flex-start
    & > .control
      &:not(:last-child)
        margin-bottom 0
        margin-right 10px
      &.is-expanded
        -webkit-box-flex 1
        -webkit-flex-grow 1
        -ms-flex-positive 1
        flex-grow 1
    &.is-grouped-centered
      -webkit-box-pack center
      -webkit-justify-content center
      -ms-flex-pack center
      justify-content center
    &.is-grouped-right
      -webkit-box-pack end
      -webkit-justify-content flex-end
      -ms-flex-pack end
      justify-content flex-end
  &.is-loading
    &:after
      position absolute !important
      right 8px
      top 8px

.control.has-addons .button,
.control.has-addons .input,
.control.has-addons .textarea,
.control.has-addons .select
  border-radius 0
  margin-right -1px
  width auto

.control.has-addons .button:hover,
.control.has-addons .input:hover,
.control.has-addons .textarea:hover,
.control.has-addons .select:hover
  z-index 2

.control.has-addons .button:active, .control.has-addons .button:focus,
.control.has-addons .input:active,
.control.has-addons .textarea:active,
.control.has-addons .input:focus,
.control.has-addons .textarea:focus,
.control.has-addons .select:active,
.control.has-addons .select:focus
  z-index 3

.control.has-addons .button:first-child,
.control.has-addons .input:first-child,
.control.has-addons .textarea:first-child,
.control.has-addons .select:first-child
  border-radius 3px 0 0 3px

.control.has-addons .button:first-child select,
.control.has-addons .input:first-child select,
.control.has-addons .textarea:first-child select,
.control.has-addons .select:first-child select
  border-radius 3px 0 0 3px

.control.has-addons .button:last-child,
.control.has-addons .input:last-child,
.control.has-addons .textarea:last-child,
.control.has-addons .select:last-child
  border-radius 0 3px 3px 0

.control.has-addons .button:last-child select,
.control.has-addons .input:last-child select,
.control.has-addons .textarea:last-child select,
.control.has-addons .select:last-child select
  border-radius 0 3px 3px 0

.control.has-addons .button.is-expanded,
.control.has-addons .input.is-expanded,
.control.has-addons .is-expanded.textarea,
.control.has-addons .select.is-expanded
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1

.control.has-addons.has-addons-fullwidth .button,
.control.has-addons.has-addons-fullwidth .input,
.control.has-addons.has-addons-fullwidth .textarea,
.control.has-addons.has-addons-fullwidth .select
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1

.control.has-icon .input:focus + .fa, .control.has-icon .textarea:focus + .fa
  color #222324

.control.has-icon .input.is-small + .fa, .control.has-icon .is-small.textarea + .fa
  font-size 10.5px
  top 0

.control.has-icon .input.is-medium + .fa, .control.has-icon .is-medium.textarea + .fa
  font-size 21px
  top 8px

.control.has-icon .input.is-large + .fa, .control.has-icon .is-large.textarea + .fa
  font-size 21px
  top 12px

.control.has-icon:not(.has-icon-right) .input, .control.has-icon:not(.has-icon-right) .textarea
  padding-left 32px

.control.has-icon:not(.has-icon-right) .input.is-small, .control.has-icon:not(.has-icon-right) .is-small.textarea
  padding-left 24px

.control.has-icon:not(.has-icon-right) .input.is-small + .fa, .control.has-icon:not(.has-icon-right) .is-small.textarea + .fa
  left 0

.control.has-icon:not(.has-icon-right) .input.is-medium, .control.has-icon:not(.has-icon-right) .is-medium.textarea
  padding-left 40px

.control.has-icon:not(.has-icon-right) .input.is-medium + .fa, .control.has-icon:not(.has-icon-right) .is-medium.textarea + .fa
  left 8px

.control.has-icon:not(.has-icon-right) .input.is-large, .control.has-icon:not(.has-icon-right) .is-large.textarea
  padding-left 48px

.control.has-icon:not(.has-icon-right) .input.is-large + .fa, .control.has-icon:not(.has-icon-right) .is-large.textarea + .fa
  left 12px

.control.has-icon.has-icon-right .input, .control.has-icon.has-icon-right .textarea
  padding-right 32px

.control.has-icon.has-icon-right .input.is-small, .control.has-icon.has-icon-right .is-small.textarea
  padding-right 24px

.control.has-icon.has-icon-right .input.is-small + .fa, .control.has-icon.has-icon-right .is-small.textarea + .fa
  right 0

.control.has-icon.has-icon-right .input.is-medium, .control.has-icon.has-icon-right .is-medium.textarea
  padding-right 40px

.control.has-icon.has-icon-right .input.is-medium + .fa, .control.has-icon.has-icon-right .is-medium.textarea + .fa
  right 8px

.control.has-icon.has-icon-right .input.is-large, .control.has-icon.has-icon-right .is-large.textarea
  padding-right 48px

.control.has-icon.has-icon-right .input.is-large + .fa, .control.has-icon.has-icon-right .is-large.textarea + .fa
  right 12px

@media screen and (min-width: 769px)
  .control
    &.is-horizontal
      display -webkit-box
      display -webkit-flex
      display -ms-flexbox
      display flex
      & > .control
        display -webkit-box
        display -webkit-flex
        display -ms-flexbox
        display flex
        -webkit-box-flex 5
        -webkit-flex-grow 5
        -ms-flex-positive 5
        flex-grow 5

.image
  display block
  position relative
  img
    display block
    height auto
    width 100%
  &.is-4by3
    padding-top 75%
  &.is-3by2
    padding-top 66.6666%
  &.is-16by9
    padding-top 56.25%
  &.is-2by1
    padding-top 50%
  &.is-16x16
    height 16px
    width 16px
  &.is-24x24
    height 24px
    width 24px
  &.is-32x32
    height 32px
    width 32px
  &.is-48x48
    height 48px
    width 48px
  &.is-64x64
    height 64px
    width 64px
  &.is-96x96
    height 96px
    width 96px
  &.is-128x128
    height 128px
    width 128px

.image.is-square img, .image.is-1by1 img, .image.is-4by3 img, .image.is-3by2 img, .image.is-16by9 img, .image.is-2by1 img
  bottom 0
  left 0
  position absolute
  right 0
  top 0
  height 100%
  width 100%

.image.is-square, .image.is-1by1
  padding-top 100%

.notification
  background-color #f5f7fa
  border-radius 3px
  padding 16px 20px
  position relative
  &:after
    clear both
    content " "
    display table
  &.is-white
    background-color #fff
    color #111
  &.is-black
    background-color #111
    color #fff
  &.is-light
    background-color #f5f7fa
    color #69707a
  &.is-dark
    background-color #69707a
    color #f5f7fa
  &.is-primary
    background-color #1fc8db
    color white
  &.is-info
    background-color #42afe3
    color white
  &.is-success
    background-color #97cd76
    color white
  &.is-warning
    background-color #fce473
    color rgba(17, 17, 17, 0.5)
  &.is-danger
    background-color #ed6c63
    color white

.notification .delete, .notification .modal-close
  border-radius 0 3px
  float right
  margin -16px -20px 0 20px

.notification .subtitle,
.notification .title
  color inherit

.progress
  -moz-appearance none
  -webkit-appearance none
  border none
  border-radius 290486px
  display block
  height 12px
  overflow hidden
  padding 0
  width 100%
  &::-webkit-progress-bar
    background-color #d3d6db
  &::-webkit-progress-value
    background-color #69707a
  &::-moz-progress-bar
    background-color #69707a
  &.is-white
    &::-webkit-progress-value
      background-color #fff
    &::-moz-progress-bar
      background-color #fff
  &.is-black
    &::-webkit-progress-value
      background-color #111
    &::-moz-progress-bar
      background-color #111
  &.is-light
    &::-webkit-progress-value
      background-color #f5f7fa
    &::-moz-progress-bar
      background-color #f5f7fa
  &.is-dark
    &::-webkit-progress-value
      background-color #69707a
    &::-moz-progress-bar
      background-color #69707a
  &.is-primary
    &::-webkit-progress-value
      background-color #1fc8db
    &::-moz-progress-bar
      background-color #1fc8db
  &.is-info
    &::-webkit-progress-value
      background-color #42afe3
    &::-moz-progress-bar
      background-color #42afe3
  &.is-success
    &::-webkit-progress-value
      background-color #97cd76
    &::-moz-progress-bar
      background-color #97cd76
  &.is-warning
    &::-webkit-progress-value
      background-color #fce473
    &::-moz-progress-bar
      background-color #fce473
  &.is-danger
    &::-webkit-progress-value
      background-color #ed6c63
    &::-moz-progress-bar
      background-color #ed6c63
  &.is-small
    height 8px
  &.is-medium
    height 16px
  &.is-large
    height 20px

.table
  background-color #fff
  color #222324
  margin-bottom 20px
  width 100%
  th
    color #222324
    text-align left
  tr
    &:hover
      background-color #f5f7fa
      color #222324
  &.is-striped
    tbody
      tr
        &:hover
          background-color #eef2f7
        &:nth-child(2n)
          background-color #f5f7fa
        &:nth-child(2n):hover
          background-color #eef2f7

.table td,
.table th
  border 1px solid #d3d6db
  border-width 0 0 1px
  padding 8px 10px
  vertical-align top

.table td.is-icon,
.table th.is-icon
  padding 5px
  text-align center
  white-space nowrap
  width 1%

.table td.is-icon .fa,
.table th.is-icon .fa
  display inline-block
  font-size 21px
  height 24px
  line-height 24px
  text-align center
  vertical-align top
  width 24px

.table td.is-icon.is-link,
.table th.is-icon.is-link
  padding 0

.table td.is-icon.is-link > a,
.table th.is-icon.is-link > a
  padding 5px

.table td.is-link,
.table th.is-link
  padding 0

.table td.is-link > a,
.table th.is-link > a
  display block
  padding 8px 10px

.table td.is-link > a:hover,
.table th.is-link > a:hover
  background-color #1fc8db
  color white

.table td.is-narrow,
.table th.is-narrow
  white-space nowrap
  width 1%

.table thead td,
.table thead th
  border-width 0 0 2px
  color #aeb1b5

.table tbody tr:last-child td,
.table tbody tr:last-child th
  border-bottom-width 0

.table tfoot td,
.table tfoot th
  border-width 2px 0 0
  color #aeb1b5

.table.is-bordered td,
.table.is-bordered th
  border-width 1px

.table.is-bordered tr:last-child td,
.table.is-bordered tr:last-child th
  border-bottom-width 1px

.table.is-narrow td,
.table.is-narrow th
  padding 5px 10px

.table.is-narrow td.is-icon,
.table.is-narrow th.is-icon
  padding 2px

.table.is-narrow td.is-icon.is-link,
.table.is-narrow th.is-icon.is-link
  padding 0

.table.is-narrow td.is-icon.is-link > a,
.table.is-narrow th.is-icon.is-link > a
  padding 2px

.table.is-narrow td.is-link,
.table.is-narrow th.is-link
  padding 0

.table.is-narrow td.is-link > a,
.table.is-narrow th.is-link > a
  padding 5px 10px

.title,
.subtitle
  font-weight 300
  word-break break-word

.title em,
.title span,
.subtitle em,
.subtitle span
  font-weight 300

.title a:hover,
.subtitle a:hover
  border-bottom 1px solid

.title strong,
.subtitle strong
  font-weight 500

.title .tag,
.subtitle .tag
  vertical-align bottom

.title
  color #222324
  font-size 28px
  line-height 1
  code
    display inline-block
    font-size 28px
  strong
    color inherit
  & + .highlight
    margin-top -10px
  & + .subtitle
    margin-top -10px
  &.is-1
    font-size 48px
    code
      font-size 40px
  &.is-2
    font-size 40px
    code
      font-size 28px
  &.is-3
    font-size 28px
    code
      font-size 24px
  &.is-4
    font-size 24px
    code
      font-size 18px
  &.is-5
    font-size 18px
    code
      font-size 14px
  &.is-6
    font-size 14px
    code
      font-size 14px
  &.is-normal
    font-weight 400
    strong
      font-weight 700

@media screen and (min-width: 769px)
  .title
    & + .subtitle
      margin-top -15px

.subtitle
  color #69707a
  font-size 18px
  line-height 1.125
  code
    border-radius 3px
    display inline-block
    font-size 14px
    padding 2px 3px
    vertical-align top
  strong
    color #222324
  & + .title
    margin-top -20px
  &.is-1
    font-size 48px
    code
      font-size 40px
  &.is-2
    font-size 40px
    code
      font-size 28px
  &.is-3
    font-size 28px
    code
      font-size 24px
  &.is-4
    font-size 24px
    code
      font-size 18px
  &.is-5
    font-size 18px
    code
      font-size 14px
  &.is-6
    font-size 14px
    code
      font-size 14px
  &.is-normal
    font-weight 400
    strong
      font-weight 700

.delete, .modal-close
  -moz-appearance none
  -webkit-appearance none
  background-color rgba(17, 17, 17, 0.2)
  border none
  border-radius 290486px
  cursor pointer
  display inline-block
  height 24px
  position relative
  vertical-align top
  width 24px

.delete:before, .modal-close:before, .delete:after, .modal-close:after
  background-color #fff
  content ""
  display block
  height 2px
  left 50%
  margin-left -25%
  margin-top -1px
  position absolute
  top 50%
  width 50%

.delete:before, .modal-close:before
  -webkit-transform rotate(45deg)
  transform rotate(45deg)

.delete:after, .modal-close:after
  -webkit-transform rotate(-45deg)
  transform rotate(-45deg)

.delete:hover, .modal-close:hover
  background-color rgba(17, 17, 17, 0.5)

.delete.is-small, .tag:not(.is-large) .delete, .tag:not(.is-large) .modal-close, .is-small.modal-close
  height 16px
  width 16px

.delete.is-medium, .is-medium.modal-close
  height 32px
  width 32px

.delete.is-large, .is-large.modal-close
  height 40px
  width 40px

.icon
  display inline-block
  font-size 21px
  height 24px
  line-height 24px
  text-align center
  vertical-align top
  width 24px
  .fa
    font-size inherit
    line-height inherit
  &.is-small
    display inline-block
    font-size 14px
    height 16px
    line-height 16px
    text-align center
    vertical-align top
    width 16px
  &.is-medium
    display inline-block
    font-size 28px
    height 32px
    line-height 32px
    text-align center
    vertical-align top
    width 32px
  &.is-large
    display inline-block
    font-size 42px
    height 48px
    line-height 48px
    text-align center
    vertical-align top
    width 48px

.hamburger, .nav-toggle
  cursor pointer
  display block
  height 50px
  position relative
  width 50px

.hamburger span, .nav-toggle span
  background-color #69707a
  display block
  height 1px
  left 50%
  margin-left -7px
  position absolute
  top 50%
  -webkit-transition none 86ms ease-out
  transition none 86ms ease-out
  -webkit-transition-property background, left, opacity, -webkit-transform
  transition-property background, left, opacity, -webkit-transform
  transition-property background, left, opacity, transform
  transition-property background, left, opacity, transform, -webkit-transform
  width 15px

.hamburger span:nth-child(1), .nav-toggle span:nth-child(1)
  margin-top -6px

.hamburger span:nth-child(2), .nav-toggle span:nth-child(2)
  margin-top -1px

.hamburger span:nth-child(3), .nav-toggle span:nth-child(3)
  margin-top 4px

.hamburger:hover, .nav-toggle:hover
  background-color #f5f7fa

.hamburger.is-active span, .is-active.nav-toggle span
  background-color #1fc8db

.hamburger.is-active span:nth-child(1), .is-active.nav-toggle span:nth-child(1)
  margin-left -5px
  -webkit-transform rotate(45deg)
  transform rotate(45deg)
  -webkit-transform-origin left top
  transform-origin left top

.hamburger.is-active span:nth-child(2), .is-active.nav-toggle span:nth-child(2)
  opacity 0

.hamburger.is-active span:nth-child(3), .is-active.nav-toggle span:nth-child(3)
  margin-left -5px
  -webkit-transform rotate(-45deg)
  transform rotate(-45deg)
  -webkit-transform-origin left bottom
  transform-origin left bottom

.heading
  display block
  font-size 11px
  letter-spacing 1px
  margin-bottom 5px
  text-transform uppercase

.highlight
  font-size 12px
  font-weight normal
  max-width 100%
  overflow hidden
  padding 0
  background-color #fdf6e3
  color #586e75
  pre
    overflow auto
    max-width 100%
  .c
    color #93a1a1
  .k
    color #859900
  .o
    color #859900
  .x
    color #cb4b16
  .p
    color #586e75
  .cm
    color #93a1a1
  .cp
    color #859900
  .c1
    color #93a1a1
  .cs
    color #859900
  .gd
    color #2aa198
  .ge
    color #586e75
    font-style italic
  .gr
    color #dc322f
  .gh
    color #cb4b16
  .gi
    color #859900
  .gs
    color #586e75
    font-weight bold
  .gu
    color #cb4b16
  .gt
    color #586e75
  .kc
    color #cb4b16
  .kd
    color #268bd2
  .kr
    color #268bd2
  .kt
    color #dc322f
  .ld
    color #586e75
  .na
    color #B58900
  .nb
    color #586e75
  .nc
    color #268bd2
  .no
    color #cb4b16
  .nd
    color #268bd2
  .nf
    color #268bd2
  .ow
    color #859900
  .w
    color #586e75
  .sb
    color #93a1a1
  .sc
    color #2aa198
  .sd
    color #586e75
  .s2
    color #2aa198
  .se
    color #cb4b16
  .sh
    color #586e75
  .sr
    color #dc322f
  .il
    color #2aa198

.loader, .button.is-loading:after, .control.is-loading:after
  -webkit-animation spin-around 500ms infinite linear
  animation spin-around 500ms infinite linear
  border 2px solid #d3d6db
  border-radius 290486px
  border-right-color transparent
  border-top-color transparent
  content ""
  display block
  height 16px
  position relative
  width 16px

.number
  background-color #f5f7fa
  border-radius 290486px
  display inline-block
  font-size 18px
  vertical-align top

.tag
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  align-items center
  background-color #f5f7fa
  border-radius 290486px
  color #69707a
  display -webkit-inline-box
  display -webkit-inline-flex
  display -ms-inline-flexbox
  display inline-flex
  font-size 12px
  height 24px
  -webkit-box-pack center
  -webkit-justify-content center
  -ms-flex-pack center
  justify-content center
  line-height 16px
  padding-left 10px
  padding-right 10px
  vertical-align top
  white-space nowrap
  &.is-white
    background-color #fff
    color #111
  &.is-black
    background-color #111
    color #fff
  &.is-light
    background-color #f5f7fa
    color #69707a
  &.is-dark
    background-color #69707a
    color #f5f7fa
  &.is-primary
    background-color #1fc8db
    color white
  &.is-info
    background-color #42afe3
    color white
  &.is-success
    background-color #97cd76
    color white
  &.is-warning
    background-color #fce473
    color rgba(17, 17, 17, 0.5)
  &.is-danger
    background-color #ed6c63
    color white
  &.is-small
    font-size 11px
    height 20px
    padding-left 8px
    padding-right 8px
  &.is-medium
    font-size 14px
    height 32px
    padding-left 14px
    padding-right 14px
  &.is-large
    font-size 18px
    height 40px
    line-height 24px
    padding-left 18px
    padding-right 18px

.tag .delete, .tag .modal-close
  margin-left 4px
  margin-right -6px

.tag.is-large .delete, .tag.is-large .modal-close
  margin-left 4px
  margin-right -8px

.unselectable, .is-unselectable, .button, .delete, .modal-close, .tabs
  -webkit-touch-callout none
  -webkit-user-select none
  -moz-user-select none
  -ms-user-select none
  user-select none

.card-header
  -webkit-box-align stretch
  -webkit-align-items stretch
  -ms-flex-align stretch
  align-items stretch
  box-shadow 0 1px 2px rgba(17, 17, 17, 0.1)
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  min-height 40px

.card-header-title
  -webkit-box-align start
  -webkit-align-items flex-start
  -ms-flex-align start
  align-items flex-start
  color #222324
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1
  font-weight bold
  padding 10px

.card-header-icon
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  align-items center
  cursor pointer
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-pack center
  -webkit-justify-content center
  -ms-flex-pack center
  justify-content center
  width 40px

.card-image
  display block
  position relative

.card-content
  padding 20px
  .title
    & + .subtitle
      margin-top -20px

.card-footer
  border-top 1px solid #d3d6db
  -webkit-box-align stretch
  -webkit-align-items stretch
  -ms-flex-align stretch
  align-items stretch
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex

.card-footer-item
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  align-items center
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1
  -webkit-box-pack center
  -webkit-justify-content center
  -ms-flex-pack center
  justify-content center
  padding 10px
  &:not(:last-child)
    border-right 1px solid #d3d6db

.card
  background-color #fff
  box-shadow 0 2px 3px rgba(17, 17, 17, 0.1), 0 0 0 1px rgba(17, 17, 17, 0.1)
  color #69707a
  max-width 100%
  position relative
  width 300px
  .media
    &:not(:last-child)
      margin-bottom 10px
  &.is-fullwidth
    width 100%
  &.is-rounded
    border-radius 5px

.column
  -webkit-flex-basis 0
  -ms-flex-preferred-size 0
  flex-basis 0
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1
  -webkit-flex-shrink 1
  -ms-flex-negative 1
  flex-shrink 1
  padding 10px

.columns
  margin-left -10px
  margin-right -10px
  margin-top -10px
  &.is-mobile
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    & > .column
      &.is-narrow
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
      &.is-full
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 100%
      &.is-three-quarters
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 75%
      &.is-two-thirds
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 66.6666%
      &.is-half
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 50%
      &.is-one-third
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 33.3333%
      &.is-one-quarter
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 25%
      &.is-offset-three-quarters
        margin-left 75%
      &.is-offset-two-thirds
        margin-left 66.6666%
      &.is-offset-half
        margin-left 50%
      &.is-offset-one-third
        margin-left 33.3333%
      &.is-offset-one-quarter
        margin-left 25%
      &.is-1
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 8.33333%
      &.is-offset-1
        margin-left 8.33333%
      &.is-2
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 16.66667%
      &.is-offset-2
        margin-left 16.66667%
      &.is-3
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 25%
      &.is-offset-3
        margin-left 25%
      &.is-4
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 33.33333%
      &.is-offset-4
        margin-left 33.33333%
      &.is-5
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 41.66667%
      &.is-offset-5
        margin-left 41.66667%
      &.is-6
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 50%
      &.is-offset-6
        margin-left 50%
      &.is-7
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 58.33333%
      &.is-offset-7
        margin-left 58.33333%
      &.is-8
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 66.66667%
      &.is-offset-8
        margin-left 66.66667%
      &.is-9
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 75%
      &.is-offset-9
        margin-left 75%
      &.is-10
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 83.33333%
      &.is-offset-10
        margin-left 83.33333%
      &.is-11
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 91.66667%
      &.is-offset-11
        margin-left 91.66667%
      &.is-12
        -webkit-box-flex 0
        -webkit-flex none
        -ms-flex none
        flex none
        width 100%
      &.is-offset-12
        margin-left 100%
  &:last-child
    margin-bottom -10px
  &:not(:last-child)
    margin-bottom 10px
  &.is-centered
    -webkit-box-pack center
    -webkit-justify-content center
    -ms-flex-pack center
    justify-content center
  &.is-gapless
    margin-left 0
    margin-right 0
    margin-top 0
    &:last-child
      margin-bottom 0
    &:not(:last-child)
      margin-bottom 20px
    & > .column
      margin 0
      padding 0
  &.is-multiline
    -webkit-flex-wrap wrap
    -ms-flex-wrap wrap
    flex-wrap wrap
  &.is-vcentered
    -webkit-box-align center
    -webkit-align-items center
    -ms-flex-align center
    -ms-grid-row-align center
    align-items center

@media screen and (max-width: 768px)
  .column
    &.is-narrow-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
    &.is-full-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 100%
    &.is-three-quarters-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 75%
    &.is-two-thirds-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 66.6666%
    &.is-half-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 50%
    &.is-one-third-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 33.3333%
    &.is-one-quarter-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 25%
    &.is-offset-three-quarters-mobile
      margin-left 75%
    &.is-offset-two-thirds-mobile
      margin-left 66.6666%
    &.is-offset-half-mobile
      margin-left 50%
    &.is-offset-one-third-mobile
      margin-left 33.3333%
    &.is-offset-one-quarter-mobile
      margin-left 25%
    &.is-1-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 8.33333%
    &.is-offset-1-mobile
      margin-left 8.33333%
    &.is-2-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 16.66667%
    &.is-offset-2-mobile
      margin-left 16.66667%
    &.is-3-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 25%
    &.is-offset-3-mobile
      margin-left 25%
    &.is-4-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 33.33333%
    &.is-offset-4-mobile
      margin-left 33.33333%
    &.is-5-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 41.66667%
    &.is-offset-5-mobile
      margin-left 41.66667%
    &.is-6-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 50%
    &.is-offset-6-mobile
      margin-left 50%
    &.is-7-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 58.33333%
    &.is-offset-7-mobile
      margin-left 58.33333%
    &.is-8-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 66.66667%
    &.is-offset-8-mobile
      margin-left 66.66667%
    &.is-9-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 75%
    &.is-offset-9-mobile
      margin-left 75%
    &.is-10-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 83.33333%
    &.is-offset-10-mobile
      margin-left 83.33333%
    &.is-11-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 91.66667%
    &.is-offset-11-mobile
      margin-left 91.66667%
    &.is-12-mobile
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 100%
    &.is-offset-12-mobile
      margin-left 100%

@media screen and (min-width: 769px)   .column.is-narrow, .column.is-narrow-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none

@media screen and (min-width: 769px)   .column.is-full, .column.is-full-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 100%

@media screen and (min-width: 769px)   .column.is-three-quarters, .column.is-three-quarters-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 75%

@media screen and (min-width: 769px)   .column.is-two-thirds, .column.is-two-thirds-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 66.6666%

@media screen and (min-width: 769px)   .column.is-half, .column.is-half-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 50%

@media screen and (min-width: 769px)   .column.is-one-third, .column.is-one-third-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 33.3333%

@media screen and (min-width: 769px)   .column.is-one-quarter, .column.is-one-quarter-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 25%

@media screen and (min-width: 769px)   .column.is-offset-three-quarters, .column.is-offset-three-quarters-tablet
  margin-left 75%

@media screen and (min-width: 769px)   .column.is-offset-two-thirds, .column.is-offset-two-thirds-tablet
  margin-left 66.6666%

@media screen and (min-width: 769px)   .column.is-offset-half, .column.is-offset-half-tablet
  margin-left 50%

@media screen and (min-width: 769px)   .column.is-offset-one-third, .column.is-offset-one-third-tablet
  margin-left 33.3333%

@media screen and (min-width: 769px)   .column.is-offset-one-quarter, .column.is-offset-one-quarter-tablet
  margin-left 25%

@media screen and (min-width: 769px)   .column.is-1, .column.is-1-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 8.33333%

@media screen and (min-width: 769px)   .column.is-offset-1, .column.is-offset-1-tablet
  margin-left 8.33333%

@media screen and (min-width: 769px)   .column.is-2, .column.is-2-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 16.66667%

@media screen and (min-width: 769px)   .column.is-offset-2, .column.is-offset-2-tablet
  margin-left 16.66667%

@media screen and (min-width: 769px)   .column.is-3, .column.is-3-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 25%

@media screen and (min-width: 769px)   .column.is-offset-3, .column.is-offset-3-tablet
  margin-left 25%

@media screen and (min-width: 769px)   .column.is-4, .column.is-4-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 33.33333%

@media screen and (min-width: 769px)   .column.is-offset-4, .column.is-offset-4-tablet
  margin-left 33.33333%

@media screen and (min-width: 769px)   .column.is-5, .column.is-5-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 41.66667%

@media screen and (min-width: 769px)   .column.is-offset-5, .column.is-offset-5-tablet
  margin-left 41.66667%

@media screen and (min-width: 769px)   .column.is-6, .column.is-6-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 50%

@media screen and (min-width: 769px)   .column.is-offset-6, .column.is-offset-6-tablet
  margin-left 50%

@media screen and (min-width: 769px)   .column.is-7, .column.is-7-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 58.33333%

@media screen and (min-width: 769px)   .column.is-offset-7, .column.is-offset-7-tablet
  margin-left 58.33333%

@media screen and (min-width: 769px)   .column.is-8, .column.is-8-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 66.66667%

@media screen and (min-width: 769px)   .column.is-offset-8, .column.is-offset-8-tablet
  margin-left 66.66667%

@media screen and (min-width: 769px)   .column.is-9, .column.is-9-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 75%

@media screen and (min-width: 769px)   .column.is-offset-9, .column.is-offset-9-tablet
  margin-left 75%

@media screen and (min-width: 769px)   .column.is-10, .column.is-10-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 83.33333%

@media screen and (min-width: 769px)   .column.is-offset-10, .column.is-offset-10-tablet
  margin-left 83.33333%

@media screen and (min-width: 769px)   .column.is-11, .column.is-11-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 91.66667%

@media screen and (min-width: 769px)   .column.is-offset-11, .column.is-offset-11-tablet
  margin-left 91.66667%

@media screen and (min-width: 769px)   .column.is-12, .column.is-12-tablet
  -webkit-box-flex 0
  -webkit-flex none
  -ms-flex none
  flex none
  width 100%

@media screen and (min-width: 769px)   .column.is-offset-12, .column.is-offset-12-tablet
  margin-left 100%

@media screen and (min-width: 980px)
  .column
    &.is-narrow-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
    &.is-full-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 100%
    &.is-three-quarters-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 75%
    &.is-two-thirds-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 66.6666%
    &.is-half-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 50%
    &.is-one-third-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 33.3333%
    &.is-one-quarter-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 25%
    &.is-offset-three-quarters-desktop
      margin-left 75%
    &.is-offset-two-thirds-desktop
      margin-left 66.6666%
    &.is-offset-half-desktop
      margin-left 50%
    &.is-offset-one-third-desktop
      margin-left 33.3333%
    &.is-offset-one-quarter-desktop
      margin-left 25%
    &.is-1-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 8.33333%
    &.is-offset-1-desktop
      margin-left 8.33333%
    &.is-2-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 16.66667%
    &.is-offset-2-desktop
      margin-left 16.66667%
    &.is-3-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 25%
    &.is-offset-3-desktop
      margin-left 25%
    &.is-4-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 33.33333%
    &.is-offset-4-desktop
      margin-left 33.33333%
    &.is-5-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 41.66667%
    &.is-offset-5-desktop
      margin-left 41.66667%
    &.is-6-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 50%
    &.is-offset-6-desktop
      margin-left 50%
    &.is-7-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 58.33333%
    &.is-offset-7-desktop
      margin-left 58.33333%
    &.is-8-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 66.66667%
    &.is-offset-8-desktop
      margin-left 66.66667%
    &.is-9-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 75%
    &.is-offset-9-desktop
      margin-left 75%
    &.is-10-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 83.33333%
    &.is-offset-10-desktop
      margin-left 83.33333%
    &.is-11-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 91.66667%
    &.is-offset-11-desktop
      margin-left 91.66667%
    &.is-12-desktop
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 100%
    &.is-offset-12-desktop
      margin-left 100%

@media screen and (min-width: 1180px)
  .column
    &.is-narrow-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
    &.is-full-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 100%
    &.is-three-quarters-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 75%
    &.is-two-thirds-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 66.6666%
    &.is-half-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 50%
    &.is-one-third-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 33.3333%
    &.is-one-quarter-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 25%
    &.is-offset-three-quarters-widescreen
      margin-left 75%
    &.is-offset-two-thirds-widescreen
      margin-left 66.6666%
    &.is-offset-half-widescreen
      margin-left 50%
    &.is-offset-one-third-widescreen
      margin-left 33.3333%
    &.is-offset-one-quarter-widescreen
      margin-left 25%
    &.is-1-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 8.33333%
    &.is-offset-1-widescreen
      margin-left 8.33333%
    &.is-2-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 16.66667%
    &.is-offset-2-widescreen
      margin-left 16.66667%
    &.is-3-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 25%
    &.is-offset-3-widescreen
      margin-left 25%
    &.is-4-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 33.33333%
    &.is-offset-4-widescreen
      margin-left 33.33333%
    &.is-5-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 41.66667%
    &.is-offset-5-widescreen
      margin-left 41.66667%
    &.is-6-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 50%
    &.is-offset-6-widescreen
      margin-left 50%
    &.is-7-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 58.33333%
    &.is-offset-7-widescreen
      margin-left 58.33333%
    &.is-8-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 66.66667%
    &.is-offset-8-widescreen
      margin-left 66.66667%
    &.is-9-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 75%
    &.is-offset-9-widescreen
      margin-left 75%
    &.is-10-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 83.33333%
    &.is-offset-10-widescreen
      margin-left 83.33333%
    &.is-11-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 91.66667%
    &.is-offset-11-widescreen
      margin-left 91.66667%
    &.is-12-widescreen
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 100%
    &.is-offset-12-widescreen
      margin-left 100%

@media screen and (min-width: 769px)
  .columns
    &.is-grid
      -webkit-flex-wrap wrap
      -ms-flex-wrap wrap
      flex-wrap wrap
      & > .column
        max-width 33.3333%
        padding 10px
        width 33.3333%
        & + .column
          margin-left 0

@media screen and (min-width: 769px)
  .columns
    &:not(.is-desktop)
      display -webkit-box
      display -webkit-flex
      display -ms-flexbox
      display flex

@media screen and (min-width: 980px)
  .columns
    &.is-desktop
      display -webkit-box
      display -webkit-flex
      display -ms-flexbox
      display flex

.tile
  -webkit-box-align stretch
  -webkit-align-items stretch
  -ms-flex-align stretch
  -ms-grid-row-align stretch
  align-items stretch
  -webkit-flex-basis auto
  -ms-flex-preferred-size auto
  flex-basis auto
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1
  -webkit-flex-shrink 1
  -ms-flex-negative 1
  flex-shrink 1
  min-height -webkit-min-content
  min-height -moz-min-content
  min-height min-content
  &.is-ancestor
    margin-left -10px
    margin-right -10px
    margin-top -10px
    &:last-child
      margin-bottom -10px
    &:not(:last-child)
      margin-bottom 10px
  &.is-child
    margin 0 !important
  &.is-parent
    padding 10px
  &.is-vertical
    -webkit-box-orient vertical
    -webkit-box-direction normal
    -webkit-flex-direction column
    -ms-flex-direction column
    flex-direction column
    & > .tile
      &.is-child
        &:not(:last-child)
          margin-bottom 20px !important

@media screen and (min-width: 769px)
  .tile
    &:not(.is-child)
      display -webkit-box
      display -webkit-flex
      display -ms-flexbox
      display flex
    &.is-1
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 8.33333%
    &.is-2
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 16.66667%
    &.is-3
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 25%
    &.is-4
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 33.33333%
    &.is-5
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 41.66667%
    &.is-6
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 50%
    &.is-7
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 58.33333%
    &.is-8
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 66.66667%
    &.is-9
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 75%
    &.is-10
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 83.33333%
    &.is-11
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 91.66667%
    &.is-12
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      width 100%

.highlight .err,
.highlight .g
  color #586e75

.highlight .l,
.highlight .n
  color #586e75

.highlight .go,
.highlight .gp
  color #586e75

.highlight .kn,
.highlight .kp
  color #859900

.highlight .m,
.highlight .s
  color #2aa198

.highlight .ni,
.highlight .ne
  color #cb4b16

.highlight .nl,
.highlight .nn,
.highlight .nx,
.highlight .py
  color #586e75

.highlight .nt,
.highlight .nv
  color #268bd2

.highlight .mf,
.highlight .mh,
.highlight .mi,
.highlight .mo
  color #2aa198

.highlight .si,
.highlight .sx
  color #2aa198

.highlight .s1,
.highlight .ss
  color #2aa198

.highlight .bp,
.highlight .vc,
.highlight .vg,
.highlight .vi
  color #268bd2

.level-item .title,
.level-item .subtitle
  margin-bottom 0

@media screen and (max-width: 768px)
  .level-item
    &:not(:last-child)
      margin-bottom 10px

.level-left .level-item:not(:last-child),
.level-right .level-item:not(:last-child)
  margin-right 10px

.level-left .level-item.is-flexible,
.level-right .level-item.is-flexible
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1

@media screen and (max-width: 768px)
  .level-left
    & + .level-right
      margin-top 20px

@media screen and (min-width: 769px)
  .level-left
    -webkit-box-align center
    -webkit-align-items center
    -ms-flex-align center
    align-items center
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex

@media screen and (min-width: 769px)
  .level-right
    -webkit-box-align center
    -webkit-align-items center
    -ms-flex-align center
    align-items center
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    -webkit-box-pack end
    -webkit-justify-content flex-end
    -ms-flex-pack end
    justify-content flex-end

.level
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  -ms-grid-row-align center
  align-items center
  -webkit-box-pack justify
  -webkit-justify-content space-between
  -ms-flex-pack justify
  justify-content space-between
  code
    border-radius 3px
  img
    display inline-block
    vertical-align top
  &.is-mobile
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    & > .level-item
      &:not(:last-child)
        margin-bottom 0
      &:not(.is-narrow)
        -webkit-box-flex 1
        -webkit-flex-grow 1
        -ms-flex-positive 1
        flex-grow 1

@media screen and (min-width: 769px)
  .level
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    & > .level-item
      &:not(.is-narrow)
        -webkit-box-flex 1
        -webkit-flex-grow 1
        -ms-flex-positive 1
        flex-grow 1

.media-number
  background-color #f5f7fa
  border-radius 290486px
  display inline-block
  font-size 18px
  height 32px
  line-height 24px
  min-width 32px
  padding 4px 8px
  text-align center
  vertical-align top

@media screen and (max-width: 768px)
  .media-number
    margin-bottom 10px

@media screen and (min-width: 769px)
  .media-number
    margin-right 10px

.media-left
  margin-right 10px

.media-right
  margin-left 10px

.media-content
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1
  text-align left

.media
  -webkit-box-align start
  -webkit-align-items flex-start
  -ms-flex-align start
  align-items flex-start
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  text-align left
  .content
    &:not(:last-child)
      margin-bottom 10px
  .media
    border-top 1px solid rgba(211, 214, 219, 0.5)
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    padding-top 10px
    .media
      padding-top 5px
      & + .media
        margin-top 5px
  & + .media
    border-top 1px solid rgba(211, 214, 219, 0.5)
    margin-top 10px
    padding-top 10px
  &.is-large
    & + .media
      margin-top 20px
      padding-top 20px

.media .media .content:not(:last-child),
.media .media .control:not(:last-child)
  margin-bottom 5px

@media screen and (min-width: 769px)
  .media
    &.is-large
      .media-number
        margin-right 20px

.menu-nav
  a
    display block
    padding 5px 10px

.menu-list
  a
    border-radius 2px
    color #69707a
    display block
    padding 5px 10px
    &:hover
      background-color #f5f7fa
      color #1fc8db
    &.is-active
      background-color #1fc8db
      color white
  li
    ul
      border-left 1px solid #d3d6db
      margin 10px
      padding-left 10px

.menu-label
  color #aeb1b5
  font-size 11px
  letter-spacing 1px
  margin-bottom 5px
  text-transform uppercase
  &:not(:first-child)
    margin-top 20px

.message-body
  border 1px solid #d3d6db
  border-radius 3px
  padding 12px 15px
  strong
    color inherit

.message-header
  background-color #69707a
  border-radius 3px 3px 0 0
  color white
  padding 7px 10px
  strong
    color inherit
  & + .message-body
    border-radius 0 0 3px 3px
    border-top none

.message
  background-color #f5f7fa
  border-radius 3px
  &.is-white
    background-color white
    .message-header
      background-color #fff
      color #111
    .message-body
      border-color #fff
      color #666666
  &.is-black
    background-color whitesmoke
    .message-header
      background-color #111
      color #fff
    .message-body
      border-color #111
      color gray
  &.is-light
    background-color #f5f7fa
    .message-header
      background-color #f5f7fa
      color #69707a
    .message-body
      border-color #f5f7fa
      color #666666
  &.is-dark
    background-color #f4f5f6
    .message-header
      background-color #69707a
      color #f5f7fa
    .message-body
      border-color #69707a
      color gray
  &.is-primary
    background-color #edfbfc
    .message-header
      background-color #1fc8db
      color white
    .message-body
      border-color #1fc8db
      color gray
  &.is-info
    background-color #edf7fc
    .message-header
      background-color #42afe3
      color white
    .message-body
      border-color #42afe3
      color gray
  &.is-success
    background-color #f4faf0
    .message-header
      background-color #97cd76
      color white
    .message-body
      border-color #97cd76
      color gray
  &.is-warning
    background-color #fffbeb
    .message-header
      background-color #fce473
      color rgba(17, 17, 17, 0.5)
    .message-body
      border-color #fce473
      color #666666
  &.is-danger
    background-color #fdeeed
    .message-header
      background-color #ed6c63
      color white
    .message-body
      border-color #ed6c63
      color gray

.modal-background
  bottom 0
  left 0
  position absolute
  right 0
  top 0
  background-color rgba(17, 17, 17, 0.86)

.modal-content, .modal-card
  margin 0 20px
  max-height calc(100vh - 160px)
  overflow auto
  position relative
  width 100%

@media screen and (min-width: 769px)   .modal-content, .modal-card
  margin 0 auto
  max-height calc(100vh - 40px)
  width 640px

.modal-close
  background none
  height 40px
  position fixed
  right 20px
  top 20px
  width 40px

.modal-card
  background-color #fff
  border-radius 5px
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-orient vertical
  -webkit-box-direction normal
  -webkit-flex-direction column
  -ms-flex-direction column
  flex-direction column
  max-height calc(100vh - 40px)
  overflow hidden

.modal-card-head,
.modal-card-foot
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  align-items center
  background-color #f5f7fa
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-flex-shrink 0
  -ms-flex-negative 0
  flex-shrink 0
  -webkit-box-pack start
  -webkit-justify-content flex-start
  -ms-flex-pack start
  justify-content flex-start
  padding 20px
  position relative

.modal-card-head
  border-bottom 1px solid #d3d6db

.modal-card-title
  color #222324
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1
  font-size 24px
  line-height 1

.modal-card-foot
  border-top 1px solid #d3d6db
  .button
    &:not(:last-child)
      margin-right 10px

.modal-card-body
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1
  overflow auto
  padding 20px

.modal
  bottom 0
  left 0
  position absolute
  right 0
  top 0
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  -ms-grid-row-align center
  align-items center
  display none
  -webkit-box-pack center
  -webkit-justify-content center
  -ms-flex-pack center
  justify-content center
  overflow hidden
  position fixed
  z-index 1986
  &.is-active
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex

@media screen and (min-width: 769px)
  .nav-toggle
    display none

.nav-item
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  align-items center
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-pack center
  -webkit-justify-content center
  -ms-flex-pack center
  justify-content center
  padding 10px
  a
    -webkit-box-flex 1
    -webkit-flex-grow 1
    -ms-flex-positive 1
    flex-grow 1
  img
    max-height 24px
  .button
    & + .button
      margin-left 10px
  .tag
    &:first-child
      margin-right 5px
    &:last-child
      margin-left 5px

@media screen and (max-width: 768px)
  .nav-item
    -webkit-box-pack start
    -webkit-justify-content flex-start
    -ms-flex-pack start
    justify-content flex-start

.nav-item a,
a.nav-item
  color #69707a

.nav-item a:hover,
a.nav-item:hover
  color #222324

.nav-item a.is-active,
a.nav-item.is-active
  color #222324

.nav-item a.is-tab,
a.nav-item.is-tab
  border-bottom 1px solid transparent
  border-top 1px solid transparent
  padding-left 12px
  padding-right 12px

.nav-item a.is-tab:hover,
a.nav-item.is-tab:hover
  border-bottom 1px solid #1fc8db
  border-top 1px solid transparent

.nav-item a.is-tab.is-active,
a.nav-item.is-tab.is-active
  border-bottom 3px solid #1fc8db
  border-top 3px solid transparent
  color #1fc8db

@media screen and (max-width: 768px)
  .nav-menu
    background-color #fff
    box-shadow 0 4px 7px rgba(17, 17, 17, 0.1)
    left 0
    display none
    right 0
    top 100%
    position absolute
    .nav-item
      border-top 1px solid rgba(211, 214, 219, 0.5)
      padding 10px
    &.is-active
      display block

@media screen and (min-width: 769px) and (max-width: 979px)
  .nav-menu
    padding-right 20px

.nav-left
  -webkit-box-align stretch
  -webkit-align-items stretch
  -ms-flex-align stretch
  align-items stretch
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-flex-basis 0
  -ms-flex-preferred-size 0
  flex-basis 0
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1
  -webkit-box-pack start
  -webkit-justify-content flex-start
  -ms-flex-pack start
  justify-content flex-start
  overflow hidden
  overflow-x auto
  white-space nowrap

.nav-center
  -webkit-box-align stretch
  -webkit-align-items stretch
  -ms-flex-align stretch
  align-items stretch
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-pack center
  -webkit-justify-content center
  -ms-flex-pack center
  justify-content center
  margin-left auto
  margin-right auto

@media screen and (min-width: 769px)
  .nav-right
    -webkit-box-align stretch
    -webkit-align-items stretch
    -ms-flex-align stretch
    align-items stretch
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    -webkit-flex-basis 0
    -ms-flex-preferred-size 0
    flex-basis 0
    -webkit-box-flex 1
    -webkit-flex-grow 1
    -ms-flex-positive 1
    flex-grow 1
    -webkit-box-pack end
    -webkit-justify-content flex-end
    -ms-flex-pack end
    justify-content flex-end

.nav
  -webkit-box-align stretch
  -webkit-align-items stretch
  -ms-flex-align stretch
  align-items stretch
  background-color #fff
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  min-height 50px
  position relative
  text-align center
  z-index 2
  & > .container
    -webkit-box-align stretch
    -webkit-align-items stretch
    -ms-flex-align stretch
    align-items stretch
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    min-height 50px
    width 100%
    & > .nav-left
      & > .nav-item
        &:first-child
          &:not(.is-tab)
            padding-left 0
    & > .nav-right
      & > .nav-item
        &:last-child
          &:not(.is-tab)
            padding-right 0
  &.has-shadow
    box-shadow 0 2px 3px rgba(17, 17, 17, 0.1)

.nav > .container > .nav-left > .nav-item.is-brand:first-child,
@media screen and (max-width: 979px)   .container > .nav > .nav-left > .nav-item.is-brand:first-child
  padding-left 20px

.pagination
  -webkit-box-align center
  -webkit-align-items center
  -ms-flex-align center
  align-items center
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-pack center
  -webkit-justify-content center
  -ms-flex-pack center
  justify-content center
  text-align center
  a
    display block
    min-width 32px
    padding 3px 8px
  span
    color #aeb1b5
    display block
    margin 0 4px
  li
    margin 0 2px
  ul
    -webkit-box-align center
    -webkit-align-items center
    -ms-flex-align center
    align-items center
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    -webkit-box-flex 1
    -webkit-flex-grow 1
    -ms-flex-positive 1
    flex-grow 1
    -webkit-box-pack center
    -webkit-justify-content center
    -ms-flex-pack center
    justify-content center

@media screen and (max-width: 768px)
  .pagination
    -webkit-flex-wrap wrap
    -ms-flex-wrap wrap
    flex-wrap wrap
    & > a
      width calc(50% - 5px)
      &:not(:first-child)
        margin-left 10px
    li
      -webkit-box-flex 1
      -webkit-flex-grow 1
      -ms-flex-positive 1
      flex-grow 1
    ul
      margin-top 10px

@media screen and (min-width: 769px)
  .pagination
    & > a
      &:not(:first-child)
        -webkit-box-ordinal-group 2
        -webkit-order 1
        -ms-flex-order 1
        order 1

.panel-icon
  display inline-block
  font-size 14px
  height 16px
  line-height 16px
  text-align center
  vertical-align top
  width 16px
  color #aeb1b5
  float left
  margin 0 4px 0 -2px
  .fa
    font-size inherit
    line-height inherit

.panel-heading
  background-color #f5f7fa
  border-bottom 1px solid #d3d6db
  border-radius 4px 4px 0 0
  color #222324
  font-size 18px
  font-weight 300
  padding 10px

.panel-list
  a
    color #69707a
    &:hover
      color #1fc8db

.panel-tabs
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  font-size 11px
  padding 5px 10px 0
  -webkit-box-pack center
  -webkit-justify-content center
  -ms-flex-pack center
  justify-content center
  a
    border-bottom 1px solid #d3d6db
    margin-bottom -1px
    padding 5px
    &.is-active
      border-bottom-color #222324
      color #222324
  &:not(:last-child)
    border-bottom 1px solid #d3d6db

.panel-block
  color #222324
  display block
  line-height 16px
  padding 10px
  &:not(:last-child)
    border-bottom 1px solid #d3d6db

.panel
  border 1px solid #d3d6db
  border-radius 5px
  &:not(:last-child)
    margin-bottom 20px

.tabs
  -webkit-box-align stretch
  -webkit-align-items stretch
  -ms-flex-align stretch
  align-items stretch
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-pack justify
  -webkit-justify-content space-between
  -ms-flex-pack justify
  justify-content space-between
  line-height 24px
  overflow hidden
  overflow-x auto
  white-space nowrap
  a
    -webkit-box-align center
    -webkit-align-items center
    -ms-flex-align center
    align-items center
    border-bottom 1px solid #d3d6db
    color #69707a
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    -webkit-box-pack center
    -webkit-justify-content center
    -ms-flex-pack center
    justify-content center
    margin-bottom -1px
    padding 6px 12px
    vertical-align top
    &:hover
      border-bottom-color #222324
      color #222324
  li
    display block
    &.is-active
      a
        border-bottom-color #1fc8db
        color #1fc8db
  ul
    -webkit-box-align center
    -webkit-align-items center
    -ms-flex-align center
    align-items center
    border-bottom 1px solid #d3d6db
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    -webkit-box-flex 1
    -webkit-flex-grow 1
    -ms-flex-positive 1
    flex-grow 1
    -webkit-box-pack start
    -webkit-justify-content flex-start
    -ms-flex-pack start
    justify-content flex-start
    &.is-left
      padding-right 10px
    &.is-center
      -webkit-box-flex 0
      -webkit-flex none
      -ms-flex none
      flex none
      -webkit-box-pack center
      -webkit-justify-content center
      -ms-flex-pack center
      justify-content center
      padding-left 10px
      padding-right 10px
    &.is-right
      -webkit-box-pack end
      -webkit-justify-content flex-end
      -ms-flex-pack end
      justify-content flex-end
      padding-left 10px
  .icon
    &:first-child
      margin-right 8px
    &:last-child
      margin-left 8px
  &.is-centered
    ul
      -webkit-box-pack center
      -webkit-justify-content center
      -ms-flex-pack center
      justify-content center
  &.is-right
    ul
      -webkit-box-pack end
      -webkit-justify-content flex-end
      -ms-flex-pack end
      justify-content flex-end
  &.is-boxed
    a
      border 1px solid transparent
      border-radius 3px 3px 0 0
      padding-bottom 5px
      padding-top 5px
      &:hover
        background-color #f5f7fa
        border-bottom-color #d3d6db
    li
      &.is-active
        a
          background-color #fff
          border-color #d3d6db
          border-bottom-color transparent !important
  &.is-fullwidth
    li
      -webkit-box-flex 1
      -webkit-flex-grow 1
      -ms-flex-positive 1
      flex-grow 1
  &.is-toggle
    a
      border 1px solid #d3d6db
      margin-bottom 0
      padding-bottom 5px
      padding-top 5px
      position relative
      &:hover
        background-color #f5f7fa
        border-color #aeb1b5
        z-index 2
    li
      & + li
        margin-left -1px
      &:first-child
        a
          border-radius 3px 0 0 3px
      &:last-child
        a
          border-radius 0 3px 3px 0
      &.is-active
        a
          background-color #1fc8db
          border-color #1fc8db
          color white
          z-index 1
    ul
      border-bottom none
  &.is-small
    font-size 11px
    a
      padding 2px 8px
  &.is-medium
    font-size 18px
    a
      padding 10px 16px
  &.is-large
    font-size 28px
    a
      padding 14px 20px

.tabs.is-small.is-boxed a, .tabs.is-small.is-toggle a
  padding-bottom 1px
  padding-top 1px

.tabs.is-medium.is-boxed a, .tabs.is-medium.is-toggle a
  padding-bottom 9px
  padding-top 9px

.tabs.is-large.is-boxed a, .tabs.is-large.is-toggle a
  padding-bottom 13px
  padding-top 13px

.hero-video
  bottom 0
  left 0
  position absolute
  right 0
  top 0
  overflow hidden
  video
    left 50%
    min-height 100%
    min-width 100%
    position absolute
    top 50%
    -webkit-transform translate3d(-50%, -50%, 0)
    transform translate3d(-50%, -50%, 0)
  &.is-transparent
    opacity 0.3

@media screen and (max-width: 768px)
  .hero-video
    display none

.hero-buttons
  margin-top 20px

@media screen and (max-width: 768px)
  .hero-buttons
    .button
      display -webkit-box
      display -webkit-flex
      display -ms-flexbox
      display flex
      &:not(:last-child)
        margin-bottom 10px

@media screen and (min-width: 769px)
  .hero-buttons
    display -webkit-box
    display -webkit-flex
    display -ms-flexbox
    display flex
    -webkit-box-pack center
    -webkit-justify-content center
    -ms-flex-pack center
    justify-content center
    .button
      &:not(:last-child)
        margin-right 20px

.hero-head,
.hero-foot
  -webkit-flex-shrink 0
  -ms-flex-negative 0
  flex-shrink 0

.hero-body
  -webkit-box-flex 1
  -webkit-flex-grow 1
  -ms-flex-positive 1
  flex-grow 1
  padding 40px 20px

@media screen and (min-width: 980px)
  .hero-body
    padding-left 0
    padding-right 0

.hero
  -webkit-box-align stretch
  -webkit-align-items stretch
  -ms-flex-align stretch
  align-items stretch
  background-color #fff
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-orient vertical
  -webkit-box-direction normal
  -webkit-flex-direction column
  -ms-flex-direction column
  flex-direction column
  -webkit-box-pack justify
  -webkit-justify-content space-between
  -ms-flex-pack justify
  justify-content space-between
  .nav
    background none
    box-shadow 0 1px 0 rgba(211, 214, 219, 0.3)
  .tabs
    ul
      border-bottom none
  &.is-white
    background-color #fff
    color #111
    .title
      color #111
    .subtitle
      color rgba(17, 17, 17, 0.7)
    .nav
      box-shadow 0 1px 0 rgba(17, 17, 17, 0.2)
    .tabs
      a
        color #111
        opacity 0.5
        &:hover
          opacity 1
      li
        &.is-active
          a
            opacity 1
    &.is-bold
      background-image -webkit-linear-gradient(309deg, #e6e6e6 0%, #fff 71%, white 100%)
      background-image linear-gradient(141deg, #e6e6e6 0%, #fff 71%, white 100%)
  &.is-black
    background-color #111
    color #fff
    .title
      color #fff
    .subtitle
      color rgba(255, 255, 255, 0.7)
    .nav
      box-shadow 0 1px 0 rgba(255, 255, 255, 0.2)
    .tabs
      a
        color #fff
        opacity 0.5
        &:hover
          opacity 1
      li
        &.is-active
          a
            opacity 1
    &.is-bold
      background-image -webkit-linear-gradient(309deg, black 0%, #111 71%, #1f1c1c 100%)
      background-image linear-gradient(141deg, black 0%, #111 71%, #1f1c1c 100%)
  &.is-light
    background-color #f5f7fa
    color #69707a
    .title
      color #69707a
    .subtitle
      color rgba(105, 112, 122, 0.7)
    .nav
      box-shadow 0 1px 0 rgba(105, 112, 122, 0.2)
    .tabs
      a
        color #69707a
        opacity 0.5
        &:hover
          opacity 1
      li
        &.is-active
          a
            opacity 1
    &.is-bold
      background-image -webkit-linear-gradient(309deg, #d0e0ec 0%, #f5f7fa 71%, white 100%)
      background-image linear-gradient(141deg, #d0e0ec 0%, #f5f7fa 71%, white 100%)
  &.is-dark
    background-color #69707a
    color #f5f7fa
    .title
      color #f5f7fa
    .subtitle
      color rgba(245, 247, 250, 0.7)
    .nav
      box-shadow 0 1px 0 rgba(245, 247, 250, 0.2)
    .tabs
      a
        color #f5f7fa
        opacity 0.5
        &:hover
          opacity 1
      li
        &.is-active
          a
            opacity 1
    &.is-bold
      background-image -webkit-linear-gradient(309deg, #495a67 0%, #69707a 71%, #6e768e 100%)
      background-image linear-gradient(141deg, #495a67 0%, #69707a 71%, #6e768e 100%)
  &.is-primary
    background-color #1fc8db
    color white
    .title
      color white
    .subtitle
      color rgba(255, 255, 255, 0.7)
    .nav
      box-shadow 0 1px 0 rgba(255, 255, 255, 0.2)
    .tabs
      a
        color white
        opacity 0.5
        &:hover
          opacity 1
      li
        &.is-active
          a
            opacity 1
    &.is-bold
      background-image -webkit-linear-gradient(309deg, #0fb8ad 0%, #1fc8db 71%, #2cb5e8 100%)
      background-image linear-gradient(141deg, #0fb8ad 0%, #1fc8db 71%, #2cb5e8 100%)
  &.is-info
    background-color #42afe3
    color white
    .title
      color white
    .subtitle
      color rgba(255, 255, 255, 0.7)
    .nav
      box-shadow 0 1px 0 rgba(255, 255, 255, 0.2)
    .tabs
      a
        color white
        opacity 0.5
        &:hover
          opacity 1
      li
        &.is-active
          a
            opacity 1
    &.is-bold
      background-image -webkit-linear-gradient(309deg, #13bfdf 0%, #42afe3 71%, #53a1eb 100%)
      background-image linear-gradient(141deg, #13bfdf 0%, #42afe3 71%, #53a1eb 100%)
  &.is-success
    background-color #97cd76
    color white
    .title
      color white
    .subtitle
      color rgba(255, 255, 255, 0.7)
    .nav
      box-shadow 0 1px 0 rgba(255, 255, 255, 0.2)
    .tabs
      a
        color white
        opacity 0.5
        &:hover
          opacity 1
      li
        &.is-active
          a
            opacity 1
    &.is-bold
      background-image -webkit-linear-gradient(309deg, #8ecb45 0%, #97cd76 71%, #96d885 100%)
      background-image linear-gradient(141deg, #8ecb45 0%, #97cd76 71%, #96d885 100%)
  &.is-warning
    background-color #fce473
    color rgba(17, 17, 17, 0.5)
    .title
      color rgba(17, 17, 17, 0.5)
    .subtitle
      color rgba(17, 17, 17, 0.7)
    .nav
      box-shadow 0 1px 0 rgba(17, 17, 17, 0.2)
    .tabs
      a
        color rgba(17, 17, 17, 0.5)
        opacity 0.5
        &:hover
          opacity 1
      li
        &.is-active
          a
            opacity 1
    &.is-bold
      background-image -webkit-linear-gradient(309deg, #ffbd3d 0%, #fce473 71%, #fffe8a 100%)
      background-image linear-gradient(141deg, #ffbd3d 0%, #fce473 71%, #fffe8a 100%)
  &.is-danger
    background-color #ed6c63
    color white
    .title
      color white
    .subtitle
      color rgba(255, 255, 255, 0.7)
    .nav
      box-shadow 0 1px 0 rgba(255, 255, 255, 0.2)
    .tabs
      a
        color white
        opacity 0.5
        &:hover
          opacity 1
      li
        &.is-active
          a
            opacity 1
    &.is-bold
      background-image -webkit-linear-gradient(309deg, #f32a3e 0%, #ed6c63 71%, #f39376 100%)
      background-image linear-gradient(141deg, #f32a3e 0%, #ed6c63 71%, #f39376 100%)
  &.is-fullheight
    min-height 100vh
    .hero-body
      -webkit-box-align center
      -webkit-align-items center
      -ms-flex-align center
      align-items center
      display -webkit-box
      display -webkit-flex
      display -ms-flexbox
      display flex
      & > .container
        -webkit-box-flex 1
        -webkit-flex-grow 1
        -ms-flex-positive 1
        flex-grow 1

.hero.is-white .title a,
.hero.is-white .title strong
  color inherit

.hero.is-white .subtitle a,
.hero.is-white .subtitle strong
  color #111

@media screen and (max-width: 768px)
  .hero
    &.is-white
      .nav-menu
        background-color #fff

.hero.is-white a.nav-item,
.hero.is-white .nav-item a:not(.button)
  color rgba(17, 17, 17, 0.5)

.hero.is-white a.nav-item:hover, .hero.is-white a.nav-item.is-active,
.hero.is-white .nav-item a:not(.button):hover,
.hero.is-white .nav-item a:not(.button).is-active
  color #111

.hero.is-white .tabs.is-boxed a, .hero.is-white .tabs.is-toggle a
  color #111

.hero.is-white .tabs.is-boxed a:hover, .hero.is-white .tabs.is-toggle a:hover
  background-color rgba(17, 17, 17, 0.1)

.hero.is-white .tabs.is-boxed li.is-active a, .hero.is-white .tabs.is-boxed li.is-active a:hover, .hero.is-white .tabs.is-toggle li.is-active a, .hero.is-white .tabs.is-toggle li.is-active a:hover
  background-color #111
  border-color #111
  color #fff

@media screen and (max-width: 768px)
  .hero
    &.is-white
      .nav-toggle
        span
          background-color #111
        &:hover
          background-color rgba(17, 17, 17, 0.1)
        &.is-active
          span
            background-color #111
      .nav-menu
        .nav-item
          border-top-color rgba(17, 17, 17, 0.2)

.hero.is-black .title a,
.hero.is-black .title strong
  color inherit

.hero.is-black .subtitle a,
.hero.is-black .subtitle strong
  color #fff

@media screen and (max-width: 768px)
  .hero
    &.is-black
      .nav-menu
        background-color #111

.hero.is-black a.nav-item,
.hero.is-black .nav-item a:not(.button)
  color rgba(255, 255, 255, 0.5)

.hero.is-black a.nav-item:hover, .hero.is-black a.nav-item.is-active,
.hero.is-black .nav-item a:not(.button):hover,
.hero.is-black .nav-item a:not(.button).is-active
  color #fff

.hero.is-black .tabs.is-boxed a, .hero.is-black .tabs.is-toggle a
  color #fff

.hero.is-black .tabs.is-boxed a:hover, .hero.is-black .tabs.is-toggle a:hover
  background-color rgba(17, 17, 17, 0.1)

.hero.is-black .tabs.is-boxed li.is-active a, .hero.is-black .tabs.is-boxed li.is-active a:hover, .hero.is-black .tabs.is-toggle li.is-active a, .hero.is-black .tabs.is-toggle li.is-active a:hover
  background-color #fff
  border-color #fff
  color #111

@media screen and (max-width: 768px)
  .hero
    &.is-black
      .nav-toggle
        span
          background-color #fff
        &:hover
          background-color rgba(17, 17, 17, 0.1)
        &.is-active
          span
            background-color #fff
      .nav-menu
        .nav-item
          border-top-color rgba(255, 255, 255, 0.2)

.hero.is-light .title a,
.hero.is-light .title strong
  color inherit

.hero.is-light .subtitle a,
.hero.is-light .subtitle strong
  color #69707a

@media screen and (max-width: 768px)
  .hero
    &.is-light
      .nav-menu
        background-color #f5f7fa

.hero.is-light a.nav-item,
.hero.is-light .nav-item a:not(.button)
  color rgba(105, 112, 122, 0.5)

.hero.is-light a.nav-item:hover, .hero.is-light a.nav-item.is-active,
.hero.is-light .nav-item a:not(.button):hover,
.hero.is-light .nav-item a:not(.button).is-active
  color #69707a

.hero.is-light .tabs.is-boxed a, .hero.is-light .tabs.is-toggle a
  color #69707a

.hero.is-light .tabs.is-boxed a:hover, .hero.is-light .tabs.is-toggle a:hover
  background-color rgba(17, 17, 17, 0.1)

.hero.is-light .tabs.is-boxed li.is-active a, .hero.is-light .tabs.is-boxed li.is-active a:hover, .hero.is-light .tabs.is-toggle li.is-active a, .hero.is-light .tabs.is-toggle li.is-active a:hover
  background-color #69707a
  border-color #69707a
  color #f5f7fa

@media screen and (max-width: 768px)
  .hero
    &.is-light
      .nav-toggle
        span
          background-color #69707a
        &:hover
          background-color rgba(17, 17, 17, 0.1)
        &.is-active
          span
            background-color #69707a
      .nav-menu
        .nav-item
          border-top-color rgba(105, 112, 122, 0.2)

.hero.is-dark .title a,
.hero.is-dark .title strong
  color inherit

.hero.is-dark .subtitle a,
.hero.is-dark .subtitle strong
  color #f5f7fa

@media screen and (max-width: 768px)
  .hero
    &.is-dark
      .nav-menu
        background-color #69707a

.hero.is-dark a.nav-item,
.hero.is-dark .nav-item a:not(.button)
  color rgba(245, 247, 250, 0.5)

.hero.is-dark a.nav-item:hover, .hero.is-dark a.nav-item.is-active,
.hero.is-dark .nav-item a:not(.button):hover,
.hero.is-dark .nav-item a:not(.button).is-active
  color #f5f7fa

.hero.is-dark .tabs.is-boxed a, .hero.is-dark .tabs.is-toggle a
  color #f5f7fa

.hero.is-dark .tabs.is-boxed a:hover, .hero.is-dark .tabs.is-toggle a:hover
  background-color rgba(17, 17, 17, 0.1)

.hero.is-dark .tabs.is-boxed li.is-active a, .hero.is-dark .tabs.is-boxed li.is-active a:hover, .hero.is-dark .tabs.is-toggle li.is-active a, .hero.is-dark .tabs.is-toggle li.is-active a:hover
  background-color #f5f7fa
  border-color #f5f7fa
  color #69707a

@media screen and (max-width: 768px)
  .hero
    &.is-dark
      .nav-toggle
        span
          background-color #f5f7fa
        &:hover
          background-color rgba(17, 17, 17, 0.1)
        &.is-active
          span
            background-color #f5f7fa
      .nav-menu
        .nav-item
          border-top-color rgba(245, 247, 250, 0.2)

.hero.is-primary .title a,
.hero.is-primary .title strong
  color inherit

.hero.is-primary .subtitle a,
.hero.is-primary .subtitle strong
  color white

@media screen and (max-width: 768px)
  .hero
    &.is-primary
      .nav-menu
        background-color #1fc8db

.hero.is-primary a.nav-item,
.hero.is-primary .nav-item a:not(.button)
  color rgba(255, 255, 255, 0.5)

.hero.is-primary a.nav-item:hover, .hero.is-primary a.nav-item.is-active,
.hero.is-primary .nav-item a:not(.button):hover,
.hero.is-primary .nav-item a:not(.button).is-active
  color white

.hero.is-primary .tabs.is-boxed a, .hero.is-primary .tabs.is-toggle a
  color white

.hero.is-primary .tabs.is-boxed a:hover, .hero.is-primary .tabs.is-toggle a:hover
  background-color rgba(17, 17, 17, 0.1)

.hero.is-primary .tabs.is-boxed li.is-active a, .hero.is-primary .tabs.is-boxed li.is-active a:hover, .hero.is-primary .tabs.is-toggle li.is-active a, .hero.is-primary .tabs.is-toggle li.is-active a:hover
  background-color white
  border-color white
  color #1fc8db

@media screen and (max-width: 768px)
  .hero
    &.is-primary
      .nav-toggle
        span
          background-color white
        &:hover
          background-color rgba(17, 17, 17, 0.1)
        &.is-active
          span
            background-color white
      .nav-menu
        .nav-item
          border-top-color rgba(255, 255, 255, 0.2)

.hero.is-info .title a,
.hero.is-info .title strong
  color inherit

.hero.is-info .subtitle a,
.hero.is-info .subtitle strong
  color white

@media screen and (max-width: 768px)
  .hero
    &.is-info
      .nav-menu
        background-color #42afe3

.hero.is-info a.nav-item,
.hero.is-info .nav-item a:not(.button)
  color rgba(255, 255, 255, 0.5)

.hero.is-info a.nav-item:hover, .hero.is-info a.nav-item.is-active,
.hero.is-info .nav-item a:not(.button):hover,
.hero.is-info .nav-item a:not(.button).is-active
  color white

.hero.is-info .tabs.is-boxed a, .hero.is-info .tabs.is-toggle a
  color white

.hero.is-info .tabs.is-boxed a:hover, .hero.is-info .tabs.is-toggle a:hover
  background-color rgba(17, 17, 17, 0.1)

.hero.is-info .tabs.is-boxed li.is-active a, .hero.is-info .tabs.is-boxed li.is-active a:hover, .hero.is-info .tabs.is-toggle li.is-active a, .hero.is-info .tabs.is-toggle li.is-active a:hover
  background-color white
  border-color white
  color #42afe3

@media screen and (max-width: 768px)
  .hero
    &.is-info
      .nav-toggle
        span
          background-color white
        &:hover
          background-color rgba(17, 17, 17, 0.1)
        &.is-active
          span
            background-color white
      .nav-menu
        .nav-item
          border-top-color rgba(255, 255, 255, 0.2)

.hero.is-success .title a,
.hero.is-success .title strong
  color inherit

.hero.is-success .subtitle a,
.hero.is-success .subtitle strong
  color white

@media screen and (max-width: 768px)
  .hero
    &.is-success
      .nav-menu
        background-color #97cd76

.hero.is-success a.nav-item,
.hero.is-success .nav-item a:not(.button)
  color rgba(255, 255, 255, 0.5)

.hero.is-success a.nav-item:hover, .hero.is-success a.nav-item.is-active,
.hero.is-success .nav-item a:not(.button):hover,
.hero.is-success .nav-item a:not(.button).is-active
  color white

.hero.is-success .tabs.is-boxed a, .hero.is-success .tabs.is-toggle a
  color white

.hero.is-success .tabs.is-boxed a:hover, .hero.is-success .tabs.is-toggle a:hover
  background-color rgba(17, 17, 17, 0.1)

.hero.is-success .tabs.is-boxed li.is-active a, .hero.is-success .tabs.is-boxed li.is-active a:hover, .hero.is-success .tabs.is-toggle li.is-active a, .hero.is-success .tabs.is-toggle li.is-active a:hover
  background-color white
  border-color white
  color #97cd76

@media screen and (max-width: 768px)
  .hero
    &.is-success
      .nav-toggle
        span
          background-color white
        &:hover
          background-color rgba(17, 17, 17, 0.1)
        &.is-active
          span
            background-color white
      .nav-menu
        .nav-item
          border-top-color rgba(255, 255, 255, 0.2)

.hero.is-warning .title a,
.hero.is-warning .title strong
  color inherit

.hero.is-warning .subtitle a,
.hero.is-warning .subtitle strong
  color rgba(17, 17, 17, 0.5)

@media screen and (max-width: 768px)
  .hero
    &.is-warning
      .nav-menu
        background-color #fce473

.hero.is-warning a.nav-item,
.hero.is-warning .nav-item a:not(.button)
  color rgba(17, 17, 17, 0.5)

.hero.is-warning a.nav-item:hover, .hero.is-warning a.nav-item.is-active,
.hero.is-warning .nav-item a:not(.button):hover,
.hero.is-warning .nav-item a:not(.button).is-active
  color rgba(17, 17, 17, 0.5)

.hero.is-warning .tabs.is-boxed a, .hero.is-warning .tabs.is-toggle a
  color rgba(17, 17, 17, 0.5)

.hero.is-warning .tabs.is-boxed a:hover, .hero.is-warning .tabs.is-toggle a:hover
  background-color rgba(17, 17, 17, 0.1)

.hero.is-warning .tabs.is-boxed li.is-active a, .hero.is-warning .tabs.is-boxed li.is-active a:hover, .hero.is-warning .tabs.is-toggle li.is-active a, .hero.is-warning .tabs.is-toggle li.is-active a:hover
  background-color rgba(17, 17, 17, 0.5)
  border-color rgba(17, 17, 17, 0.5)
  color #fce473

@media screen and (max-width: 768px)
  .hero
    &.is-warning
      .nav-toggle
        span
          background-color rgba(17, 17, 17, 0.5)
        &:hover
          background-color rgba(17, 17, 17, 0.1)
        &.is-active
          span
            background-color rgba(17, 17, 17, 0.5)
      .nav-menu
        .nav-item
          border-top-color rgba(17, 17, 17, 0.2)

.hero.is-danger .title a,
.hero.is-danger .title strong
  color inherit

.hero.is-danger .subtitle a,
.hero.is-danger .subtitle strong
  color white

@media screen and (max-width: 768px)
  .hero
    &.is-danger
      .nav-menu
        background-color #ed6c63

.hero.is-danger a.nav-item,
.hero.is-danger .nav-item a:not(.button)
  color rgba(255, 255, 255, 0.5)

.hero.is-danger a.nav-item:hover, .hero.is-danger a.nav-item.is-active,
.hero.is-danger .nav-item a:not(.button):hover,
.hero.is-danger .nav-item a:not(.button).is-active
  color white

.hero.is-danger .tabs.is-boxed a, .hero.is-danger .tabs.is-toggle a
  color white

.hero.is-danger .tabs.is-boxed a:hover, .hero.is-danger .tabs.is-toggle a:hover
  background-color rgba(17, 17, 17, 0.1)

.hero.is-danger .tabs.is-boxed li.is-active a, .hero.is-danger .tabs.is-boxed li.is-active a:hover, .hero.is-danger .tabs.is-toggle li.is-active a, .hero.is-danger .tabs.is-toggle li.is-active a:hover
  background-color white
  border-color white
  color #ed6c63

@media screen and (max-width: 768px)
  .hero
    &.is-danger
      .nav-toggle
        span
          background-color white
        &:hover
          background-color rgba(17, 17, 17, 0.1)
        &.is-active
          span
            background-color white
      .nav-menu
        .nav-item
          border-top-color rgba(255, 255, 255, 0.2)

@media screen and (min-width: 769px)
  .hero
    &.is-medium
      .hero-body
        padding-bottom 120px
        padding-top 120px

@media screen and (min-width: 769px)
  .hero
    &.is-large
      .hero-body
        padding-bottom 240px
        padding-top 240px

.section
  background-color #fff
  padding 40px 20px

@media screen and (min-width: 980px)
  .section
    &.is-medium
      padding 120px 20px
    &.is-large
      padding 240px 20px

.footer
  background-color #f5f7fa
  padding 40px 20px 80px

.footer a, .footer a:visited
  color #69707a

.footer a:hover, .footer a:visited:hover
  color #222324

.footer a:not(.icon), .footer a:visited:not(.icon)
  border-bottom 1px solid #d3d6db

.footer a:not(.icon):hover, .footer a:visited:not(.icon):hover
  border-bottom-color #1fc8db


```

### Contact / Social Media

*Get the latest News about Web Development, Open Source, Tooling, Server & Security*

[![Twitter](https://github.frapsoft.com/social/twitter.png)](https://twitter.com/frapsoft/)[![Facebook](https://github.frapsoft.com/social/facebook.png)](https://www.facebook.com/frapsoft/)[![Google+](https://github.frapsoft.com/social/google-plus.png)](https://plus.google.com/116540931335841862774)[![Gitter](https://github.frapsoft.com/social/gitter.png)](https://gitter.im/frapsoft/frapsoft/)[![Github](https://github.frapsoft.com/social/github.png)](https://github.com/ellerbrock/)

### Development by

Developer / Author: [Maik Ellerbrock](https://github.com/ellerbrock/)  
Company: [Frapsoft](https://github.com/frapsoft/)

### License 

Copyright (c) 2016 [Maik Ellerbrock](https://github.com/ellerbrock/)  

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit-125x28.png?v=102)](https://opensource.org/licenses/mit-license.php)  

