---
reference_chats:
  - https://chatgpt.com/c/685f27ee-8744-8002-9d53-0b4821c24ed6
  - https://chatgpt.com/g/g-p-6769c88eb070819188620496e144cc1e-thinking-or-learning-to-learn/c/685ea6ee-d7c4-8002-acaf-a3e6a77764e3?model=gpt-4o
---
1. u=f(state ) ; {cases : what must be true to achieve this claim , or what must be true in the theory's pov claim because we can't achieve theory , something mvp needs to come first then we tool as we go ? will this claim a set of cases i need to at least intersect in my react tool , between them enforcing ?}

2. Components in React are functions of states , that's what i know for now .( one part of the ui state claim above ) : {}


3. are there other blocks in react that use state ui theory ?{maybe some global storage or something ? is html only available through react components ? i guess some state manager components ? components + state managers , what does a component mean ? is it anything that can take props ? such as functions props and class what ( props too ? ) ? }


are components here , the only html managers , meaning the html can only be used from a component , therefore state can only be found in components , but there's js too that has state in it , like event listeners mapped to functions ( from a server or something ) .

	is ui function of state , meaning just the inversion of control of all the states ( the user enters his state there , the components takes them ) , but is there something else along the tree as state ?


the tree , vdom , is it the representative of all states possible that can change before the DOM representation , that's what react thinks at least , he needs to have a representation of all possbile ui states that can change in his head ( object representation ) , then everything else calls this place to register ? of course , he needs all the truths in one place , but does it have to be readable by us too like an object or he needs to represent it best . are we passing data until it finds its way in the Vdom , the Vdom is the only one that will ask the browser to push stuff , so there's no leakage between other react suff and the vdom , it's purely in the vdom and dom space , i guess the vdom will do what you ask it to do it in components and other stuff ,  


try {{
2. React's building blocks are components , composed of html as lower level type blocks . ( map of html types )
they're typed html with the properties and options you choose to include in . 
3. React enforces ui as state ? React is not a framework , so does it enforce really ? can a library enforce ? React provides Components definition for me , so components are only under React module .
4. should the logic of defining Components be encapsulated in 1 place only ? {
	 1. well , yes , so it doesn't result into multiple definition of the same components , also is there in a formal method " 1 src of truth for an object is needed or needs to be true , or the theorem should be solved and presented only once as in definition  "
		1.  ui libraries can have different definitions of the same html element , but they both can only use React's definition in the first place .
}
}}