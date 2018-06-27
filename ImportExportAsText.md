The import/export function uses a string of text, limited to simple words that anyone can use.
Repeated tiles will be condesed to the first one and a counter after it, for example `forward forward forward` would become `forward 3`
There will also be a setup function that the teacher can customise, which is hosted on the pi.
The setup function could be things like gamemode and rules, we can just leave it open at this point to give us more options.
To use the setup function all they have to do is add its name to the start of the import string.
For example: `banana forward 3 right reverse 2` would import the banana function and then parse the rest.
The function could either be setup instructions or just extra movement instructions, we'll work out the format for it later.
