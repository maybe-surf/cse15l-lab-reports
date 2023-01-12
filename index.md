Hello world.
*Italic*

**bold**

# Heading 1
## Heading2

[Link](https://github.com/maybe-surf/cse15l-lab-reports)

![Image]
(https://en.wikipedia.org/wiki/Geisel_Library)

>Blockquote

*List
*List
*List

1. One
2. Two
3. Three

Horizontal rule:
---
'Inline code' with
backticks

# code block
public class CSE12{
    private int numStudents;
    public CSE12(){
        numStudents = 0;
    }
    public CSE12(int num){
        numStudents = num;
    }

    public int getNum(){
        return numStudents;
    }
    public int officeHour(){
        return numStudents/8;
    }
    public static void main(String[] args){
        CSE12 ref = new CSE12(660);
        System.out.println(ref.getNum());
    }
}
