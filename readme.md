# I'm learning React — [ReactForBeginners.com](https://ReactForBeginners.com)

I'm learning React, starting with Wes Bos' wonderful React tutorial. I'm going to be taking notes and they'll be right here in the readme

#### this.props
###### this - refers to the component being referenced
###### props - object passed 
    - available anywhere in the component's return block
    - $r in console shows current component
    - $r.props / $r.props.tagline

you don't need a full react component if just rendering html, just need a stateless functional component
    - change react component class to a constant, passing (props):
        - const Header = props => {

