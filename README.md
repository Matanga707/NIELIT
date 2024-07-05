#@title Welcome to string 


text ='value'               #@param{type:"string"}

content='value'             #@param{type:"raw"}

drop down ='1st option'     #@param{"1st option", "2nd option","3rd option"}

text_dropdown='2nd option'  #@param{"1st option", "2nd option","3rd option"} {allow-input:true}

#@title Date fields
date_input='2024-07-4'   #@param {type:"date"}

print(text)

print(content)

print(drop down)

print(text_dropdown)

print(date_input)
