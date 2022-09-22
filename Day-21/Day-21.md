# Day-21
I am Learning CSS Pseudo Selectors By Building A Balane Sheet.

I learnt the following:
1. **[attribute="value"]** selector: `tr[class="total"]{ font-weight: bold;
   border-bottom: 4px double #0a0a23;
}; tr[class="total"] th{}`
2. `tr.total td{
  text-align: right;
  padding: 0 0.25rem;
}; tr.total td:nth-of-type(3){
  padding: 0.5rem;
}; tr.data td:last-of-type{
  padding-right: 0.5rem;
}`
3. **hover effect** : `tr.total:hover{
  background-color:#99c9ff;
};`
4. **font-style** and **font-weight** attribute: `td.current{
  font-style: italic; font-weight: normal;
}`;
5. **background image**: `background-image: linear-gradient(to bottom, #dfdfe2 1.845rem, white 1.845rem);`
6. **display** property: `display:block;`
7. **vertical-align** and **text-align** property: `text-align: right;`

Check the HTML code [here](./full-code.html)  
Check the CSS code [here](./full-code.css)