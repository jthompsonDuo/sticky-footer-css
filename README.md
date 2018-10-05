# sticky-footer-css
Flexbox solution for sticky footer

.Site {
  display: flex;
  flex-direction: column;
}
#
.Site-header,
.Site-footer {
  flex-shrink: 0; 
}
#
.Site-content {
  flex: 1 0 auto; 
}
