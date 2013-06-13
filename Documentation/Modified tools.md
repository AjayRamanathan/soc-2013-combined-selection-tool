# Modified Selection Tools

The selection tool has to be one tool for three major types of selection: 
1. **Shape** 
2. **Colour** 
3. **Content**

*Shape Selection Tool* :
A Combination of Rectangle & Ellipse Selection Tool and few new tools

*Colour Selection Tool* :
It combines Select by Colour and Fuzzy Select; and includes Multiple colour selection thus it can puesdo for Foreground Select

*Path Selection Tool* :
It combines both magnetic and free select tool, and also implements free polygon tool.

#Common Options

*This are options present in all three selection tools*

Mode [Existing]:
Default,
Addition `Shift`,
Subtraction `Ctrl`,
Intersection `Ctrl + Shift`.

Anti-aliasing [Existing]:
[Check Box]

Feather Edges [Existing]:
[Check Box] and [Radius in px; Slider] 

Other Shortcuts:
`Space` [Existing]:Panning around image

#Shape Selection Tool: 

a)Rectangle selection tool

b)Ellipse selection tool

c)Rounded rectangle selection tool

d)Single Row/Column Marquee tool:
  *As the slice tool is not yet implemented in gimp; it can be useful for web-design.*

e)Normal Polygon selection tool: 
  *Given a Integer,N,Generates only symmetric shapes.*
 
**Shortcuts**:
`Ctrl` : Start from Centre 
`Shift` : Square/Circle; Maintain Aspect Ratio

**Tool Options**

1.Expand from the Centre [Check Box]
2.Fixed [Drop Down-Menu] [Width;Height;Aspect Ratio;Size]
3.Position [Drop Down-Menu] [px,m,cm,in]: *x [Int Box] y [Int Box]*
4.Size [Drop Down-Menu] [px,m,cm,in]: *x [Integer Box]; y [Integer Box]*
5.Guides [Drop Down-Menu]
6.Rotation [Check Box] [0-360 Slider/Integer Box]
7.AutoShrink [Check Box]
8.Shrink Merged [Check Box]
9.Rounded Edges [Slider] *Only for Rounded Rectangle Selection tool*
10.Row/Column [Boolean Box] *Only for Single Row/Column Marquee tool*
11.N [Integer Box] *Only for Normal Polygon selection tool*


