# visually-hidden

.visually-hidden:not(:focus):not(:active),
input[type='checkbox'].visually-hidden,
input[type='radio'].visually-hidden {
  position: absolute;
  overflow: hidden;
  clip: rect(0 0 0 0);
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  white-space: nowrap;
  border: 0;
  clip-path: inset(100%);
}
