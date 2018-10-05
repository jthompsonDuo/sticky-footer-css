# sticky-footer-css
Flexbox solution for sticky footer

.Site {
  display: flex;
  flex-direction: column;
  height: 100vh; /* Avoid the IE 10-11 `min-height` bug. */
}
.Site-header,
.Site-footer {
  flex-shrink: 0; /* Prevent Chrome, Opera, and Safari from letting these items shrink to smaller than their content's default minimum size. */
}
.Site-content {
  flex: 1 0 auto; /* Prevent Chrome, Opera, and Safari from letting these items shrink to smaller than their content's default minimum size. */
}
