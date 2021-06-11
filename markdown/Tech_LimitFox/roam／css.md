- ```css
span.rm-page-ref[data-tag] {    
  background-color: #F4F4F4;    
  color: black;    
  padding: 3px 7px;    
  line-height: 2em;    
  border-right: solid 1px;    
  border-bottom: solid 1px;    
  border-radius: 10px;    
  font-weight: 600;
}```
- ```css
span.rm-page-ref[data-tag] {    
  background-color: #F4F4F4;    
  color: black;    
  padding: 3px 7px;    
  line-height: 2em;    
  border-right: solid 1px;    
  border-bottom: solid 1px;    
  border-radius: 10px;    
  font-weight: 600;
}

span.rm-page-ref[data-tag]::before{    
  margin-right: 10px;    
  content: '🌍';    
  display: inline-block;    
  width: 10px;    
  border-radius: 40px;    
  height: 10px;
}

span.rm-page-ref[data-tag="Source"]::before {    
  content: '📚';    
  display: inline-block;    
  width: 10px;    
  border-radius: 40px;    
  height: 10px;    
  margin-right: 10px;
}

span.rm-page-ref[data-tag="Source"] {    
  background-color: #DDF4D6;    
  color: #252422;    
  padding: 3px 7px;    
  line-height: 2em;    
  border-radius: 10px;    
  font-weight: 600;
}```
- 
