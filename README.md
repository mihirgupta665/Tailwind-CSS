# Tailwind-CSS
Revising one of the important utility based Framework Tailwind.

Tailwind: it is a framework for rapidly building modern website without ever leaving your HTML
its a "utility-first" framework which means the framework's main focus is on providing utility classes.

add this in package.json too :
"type": "module",
  "scripts": {
    "start": "vite"
  },

      /4          *4
1 -> 0.25 rem -> 4px
4 -> 1 rem -> 16px

attribute-[value_units] : sets the specified style
h-[200px] : sets height of 200px

Responsiveness : add a breakpoint prefix to the utility classes followed by a colon. eg=>   md:w-32 lg:w-48
sm : 640px
md: 768px
lg: 1024px
xl : 1280px
2xl : 1536px

Use @Apply to inline any existing utility classes inton your own custom CSS.  
In style.css file give a class then in it curly bracket area wite first @apply then give the tailwind classes . By this muliple styling will be added with you custom style name.