# form-styling
4 tutorial CSS series by Miroslaw Zelent
In the fourth episode of the CSS series, I will stylize the elements of the forms, and specifically - the inputs, ie the edit fields of the various ointments, as well as the buttons. He will share with me the ability of a distinctive stylization of editing fields, so that after this episode I will never have any problems with that! - That what he thing :)


.#HTML:

	- placeholder=""							text which disappears when we write
	- onfocus=""								when input is active					
	- onblur=""									when input lost actives

.#CSS:

	- box-shadow								set in box shadow generator add browser compatibilities -webkit- -moz-
	- input[type=text],input[type=password]{}	to styleing only that input which we want to style
	- outline: none;							active/focus input box
	- input[type=text]:focus					to style active input
	- input::-webkit-input-placeholder			styleing text placeholder for specify browsers
	
	
.# Sources:

Kurs CSS odc. 4: Stylizowanie pól formularza (inputów) by Pasja informatyki https://www.youtube.com/watch?v=9Pl0EYcndgc&list=PLOYHgt8dIdow6b2Qm3aTJbKT2BPo5iybv&index=4