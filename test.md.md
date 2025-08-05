
# Markdown 测试文件 (test.md)

这是一个用于测试 Markdown 渲染引擎的文档。我是一名程序员，所以我会重点关注代码相关的语法。

## 1. 标题 (Headings)

Markdown 支持六级标题：

# H1 标题
## H2 标题
### H3 标题
#### H4 标题
##### H5 标题
###### H6 标题

---

## 2. 段落和换行 (Paragraphs and Line Breaks)

这是一个段落。
这是同一段落中的另一行。

为了强制换行，你可以在行末添加两个空格：
这是另一行，前面有两个空格。

---

## 3. 强调 (Emphasis)

*斜体* 或 _斜体_
**粗体** 或 __粗体__
***粗斜体*** 或 ___粗斜体___

---

## 4. 列表 (Lists)

### 有序列表 (Ordered Lists)

1. 第一项
2. 第二项
   3. 嵌套项 A
   4. 嵌套项 B
5. 第三项

### 无序列表 (Unordered Lists)

* 项目 A
* 项目 B
  * 嵌套项目 1
  * 嵌套项目 2
* 项目 C

或者使用 `-` 或 `+`：

- 项目 D
- 项目 E
  + 嵌套项目 3
  + 嵌套项目 4
- 项目 F

---

## 5. 代码 (Code)

### 行内代码 (Inline Code)

这是包含行内代码 `console.log('Hello, World!');` 的文本。

### 代码块 (Code Blocks)

#### 缩进代码块 (Indented Code Blocks)

    // 这是一个缩进代码块
    function greet(name) {
        return "Hello, " + name + "!";
    }
    console.log(greet("Markdown"));

#### 围栏代码块 (Fenced Code Blocks)

```javascript
// 这是一个 JavaScript 代码块
function factorial(n) {
    if (n === 0) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}
console.log(`Factorial of 5 is: ${factorial(5)}`);
```

```python
# 这是一个 Python 代码块
def fibonacci(n):
    if n <= 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibonacci(n-1) + fibonacci(n-2)

print(f"The 10th Fibonacci number is: {fibonacci(10)}")
```

```bash
# 这是一个 Bash 代码块
echo "Hello, Bash!"
ls -l
pwd
```

```plaintext
# 这是一个没有语法高亮的纯文本代码块
This is plain text.
It does not have any specific language syntax.
```

**注意：** 确保你的渲染引擎能够正确识别和高亮不同语言的代码。

---

## 6. 引用 (Blockquotes)

> 这是第一行引用。
>
> 这是第二行引用，包含一个新段落。
>
> > 这是一个嵌套的引用。

---

## 7. 分割线 (Horizontal Rules)

使用三个或更多星号 `*`、减号 `-` 或下划线 `_` 来创建分割线：

***

---

___

---

## 8. 链接 (Links)

### 自动链接 (Automatic Links)

<https://www.example.com>
<fake@example.com>

### 参考式链接 (Reference-style Links)

这是一个 [参考式链接][ref1]。
这是另一个 [参考式链接][ref2]。

[ref1]: https://www.google.com "Google 搜索"
[ref2]: https://github.com "GitHub 官网"

### 行内链接 (Inline Links)

这是一个 [行内链接](https://developer.mozilla.org/en-US/docs/Web/Markdown "Markdown 指南")。

---

## 9. 图片 (Images)

### 行内图片 (Inline Images)

![Markdown Logo](https://markdown-here.com/img/icon256.png "Markdown 图标")

### 参考式图片 (Reference-style Images)

![Markdown Logo][logo]

[logo]: https://markdown-here.com/img/icon256.png "Markdown 图标"

---

## 10. 表格 (Tables)

Markdown 表格语法：

| Header 1 | Header 2 | Header 3 |
| :------- | :------: | -------: |
| Left     | Center   | Right    |
| Column   | Column   | Column   |
| Data     | Data     | Data     |

**说明:**
*   `:` 用于控制文本的对齐方式（左对齐、居中对齐、右对齐）。
*   表头和分隔行是必需的。

---

## 11. 任务列表 (Task Lists)

* [x] 完成的待办事项
* [ ] 未完成的待办事项
* [ ] 另一个未完成的待办事项

---

## 12. HTML (Inline HTML)

你可以在 Markdown 中嵌入 HTML：

<p>这是一个 <strong>HTML</strong> 段落。</p>
<button onclick="alert('Hello HTML!')">点击我</button>

---

## 13. 特殊字符转义 (Escaping Special Characters)

如果你想显示 Markdown 的特殊字符本身，可以使用反斜杠 `\` 进行转义：

\*星号\*
\_下划线\_
\#井号\#
\>大于号\>
\`反引号\`
\[左方括号\]
\(左圆括号\)
\{左花括号\}

---

## 14. 目录 (Table of Contents - TOC)

一些 Markdown 渲染器支持自动生成目录。这个文件本身包含的标题应该能被用来生成目录。

---

## 15. 撤销/重做 (Undo/Redo)

Ctrl+Z (撤销)
Ctrl+Y (重做)

---

## 16. 变量和常量 (Variables and Constants)

```javascript
const API_URL = "https://api.example.com/v1";
let counter = 0;
```

---

## 17. 流程控制 (Control Flow)

```python
if counter < 10:
    print("Counter is less than 10")
elif counter == 10:
    print("Counter is exactly 10")
else:
    print("Counter is greater than 10")

for i in range(5):
    print(f"Iteration: {i}")
```

---

## 18. 数据结构 (Data Structures)

```javascript
const user = {
    name: "Alice",
    age: 30,
    isActive: true
};

const numbers = [1, 2, 3, 4, 5];
```

---

## 19. 异步编程 (Asynchronous Programming)

```javascript
async function fetchData() {
    try {
        const response = await fetch(API_URL + "/users");
        const data = await response.json();
        console.log(data);
    } catch (error) {
        console.error("Error fetching data:", error);
    }
}
fetchData();
```

---

## 20. 更多代码示例 (More Code Examples)

### 命令行 (Command Line)

```bash
git clone https://github.com/your/repo.git
cd repo
npm install
npm start
```

### Dockerfile

```dockerfile
# Dockerfile example
FROM ubuntu:latest
RUN apt-get update && apt-get install -y --no-install-recommends \
    nginx \
    && rm -rf /var/lib/apt/lists/*
COPY index.html /var/www/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
```

### SQL

```sql
-- Sample SQL Query
SELECT
    customer_id,
    first_name,
    last_name,
    email
FROM
    customers
WHERE
    country = 'USA'
ORDER BY
    last_name, first_name;
```

---

## 21. 混合内容 (Mixed Content)

这是一个包含 **粗体**、*斜体* 和 `行内代码` 的段落。

```javascript
// 这是一个包含多种元素的代码块
function process(data) {
    if (data && data.length > 0) {
        data.forEach(item => {
            console.log(`Processing item: ${item.id}`);
            // 更多处理逻辑...
        });
    } else {
        console.warn("No data to process!");
    }
}
```

---

## 22. 链接到特定部分 (Linking to Specific Sections)

通常，Markdown 渲染器会为标题生成 ID，你可以链接到它们。例如，链接到“代码”部分：[代码](#代码)。

---

## 23. 脚注 (Footnotes)

这是一个带有脚注的句子[^1]。
这是另一个带有脚注的句子[^note]。

[^1]: 这是第一个脚注的内容。
[^note]: 这是第二个，更详细的脚注。

---

## 24. Emoji (如果支持)

如果你的渲染引擎支持 Emoji，这里有一些：
🚀🌟👍🎉