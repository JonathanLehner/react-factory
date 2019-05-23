# react-factory
generate react components and tests with zero boilerplate

Using:
Meteor.js
(eventually using) React Live (https://github.com/FormidableLabs/react-live)
Jest
https://draftjs.org/


With inspirations from:
https://github.com/codesandbox/codesandbox-client

Process:
- Open ReactFactory UI,
- Enter component specification (functional component yes/no),
- Enter react props + proptypes,
- Enter test cases and examples with descriptions

Result:
- Automatically generate component boilerplate 
- class XXX extends React.Component { 
   render(){
       return () 
   }
}
- Automatically generate storybook .md file with test cases and examples
- Automatically generate jest files with test cases
