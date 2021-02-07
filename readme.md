# Learning Markdown
## Table of content
    1. Tìm hiểu về markdown
    2. Các synxtax của markdown

## 1. Tìm hiểu về markdown
### 1. Markdown là gì?
    - Markdown theo góc nhìn của lập trình viên thì nó cũng giống như HTML vậy, nhưng nó viết đơn giản hơn.

### 2. Ai cần sử dụng nó?
    - Lập trình viên dùng để viết file readme mô tả cho project, dùng để hỏi bài trên stackoverflow, slack...
    - Blogger dùng để viết blog.
    - Ngoài ra bất kì ai cũng nên học nó, vì lợi ích của nó đem lại khá là thỏa công khi học nó.

### 3. Khi nào sử dụng nó
    - Nó được sử dụng trong rất nhiều trường hợp. Còn đối với mình thì mình dùng nó để viết file readme cho project, viết blog, viết content trên facebook, viết document và sau đó có thể convert sang pnd, pdf chia sẻ cho mọi người.

## 2. Các synxtax của markdown
### 1. HEADERS
    ``` # This is an <h1> tag
        ## This is an <h2> tag
        ###### This is an <h6> tag
    ```
    > Example
    - Your typing
        ```
        #### Your typing
        ```
    - Your result
        #### Your typing

### 2. EMPHASIS
    ``` *This text will be italic*
    **This text will be bold**
    *You **can** combine them*
    ```
    > Example
    - Your typing
        ```
        *You **can** combine them*
        ```
    - Your result
        *You **can** combine them*

### 3. BLOCKQUOTES
    ``` As Grace Hopper said:
    > I’ve always been more interested
    > in the future than in the past.
    ```
    > Example
    - Your typing
        ```
        As Grace Hopper said:
        > I’ve always been more interested
        > in the future than in the past.
        ```
    - Your result
        As Grace Hopper said:
        > I’ve always been more interested
        > in the future than in the past.

### 4. LISTS
    Unordered
    ``` - Item 1
        - Item 2
            - Item 2a
            - Item 2b
    ```
    Orderd
    ``` 1. Item 1
        2. Item 2
        3. Item 3
            - Item 3a
            - Item 3b
    ```
    > Example
    - Your typing
        ``` 1. Item 1
            2. Item 2
            3. Item 3
                - Item 3a
                - Item 3b
        ```
    - Your result
        1. Item 1
        2. Item 2
        3. Item 3
            - Item 3a
            - Item 3b

### 5. !IMAGES
    ``` ![GitHub Logo](/images/logo.png)
        Format: ![Alt Text](url)
    ```
    > Example
    - Your typing
        ```
        ![Facebook Logo](./default.jpg)
        ```
    - Your result
        ![Facebook Logo](./default.jpg)

### 6. LINKS
    ``` http://github.com - automatic!
        [GitHub](http://github.com)
    ```
    - Khác nhau giữa link và image là có dấu ! phía trước

    > Example
    - Your typing
        ```
        [GitHub](https://github.com/thuongnguyen-it78)
        ```
    - Your result
        [GitHub](https://github.com/thuongnguyen-it78)

### 7. BACKSLASH ESCAPES
    ``` Markdown allows you to use backslash escapes to generate literal characters which
    would otherwise have special meaning in Markdown’s formaing syntax.
    ```

    - Markdown provides backslash escapes for
the following characters:
    ```
        - \ backslash
        - ` backtick
        - * asterisk
        - _ underscore
        - {} curly braces
        - [] square brackets
        - () parentheses
        - # hash mark
        - + plus sign
        - - minus sign (hyphen)
        - . dot
        - ! exclamation mark
    ```

    > Example
    - Your typing
        ```
        \*literal asterisks\*

        ```
    - Your result
        \*literal asterisks\*

### 8. FENCED CODE BLOCKS
    ``` Markdown coverts text with four leading spaces into a code block; with GFM you can
    wrap your code with ``` to create a code block without the leading spaces. Add an
    optional language identifier and your code will get syntax highlighting.
    ```

    > Example
    - Your typing
        ```
            ```javascript
            function test() {
            console.log("look ma’, no spaces");
            }
            ```
        ```
    - Your result
        ```javascript
        function test() {
        console.log("look ma’, no spaces");
        }
        ```

### 9. TASK LISTS
    > Example
    - Your typing
        ```
            - [x] this is a complete item
            - [ ] this is an incomplete item
            - [x] @mentions, #refs, [links](),
            **formatting**, and <del>tags</del>
            supported
            - [x] list syntax required (any
            unordered or ordered list
            supported)
        ```
    - Your result
        - [x] this is a complete item
        - [ ] this is an incomplete item
        - [x] @mentions, #refs, [links](),
        **formatting**, and <del>tags</del>
        supported
        - [x] list syntax required (any
        unordered or ordered list
        supported)


### 10. USERNAME @MENTIONS
    ``` Typing an @ symbol, followed by
    a username, will notify that person
    to come and view the comment.
    This is called an “@mention”,
    because you’re mentioning the
    individual. You can also @mention
    teams within an organization.
    ```
    > Example
    - Your typing
        ```
        @thuongnguyen.it78
        ```
    - Your result
        @thuongnguyen.it78

### 11. EMOJI
    ``` To see a list of every image we
    support, check out.
    ```
    *** www.emoji-cheat-sheet.com ***
    > Example
    - Your typing
        ```
        :rocket
        ```
    - Your result
        :rocket
## Reference
    > ![markdown-cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)









