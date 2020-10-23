### 2020/10/23

##### C++中push_back()函数

push_back()函数的用法,
函数将一个新的元素加到vector的最后面，位置为当前最后一个元素的下一个元素



------

push_back()在vector最后添加一个元素（参数为要插入的值）
`    int a = 10;    vertor res;    res.push_back(a) `

------

```
pop_back() //移除最后一个元素
clear() //清空所有元素
empty() // 判断vector是否为空，如果返回true为空
erase() //删除指定元素
```

### C++ STL--queue的使用方法
    2、queue 队列
    queue模板类的定义在<queue>头文件中。
    与stack模板类很相似，queue模板类也需要两个模板参数，一个是元素类型，一个是容器类型，元素类型是必须要的，容器类型是可选的，默认是duque类型。
    定义queue对象的实例代码如下：
    <code>
    queue<int> q1;
    queue<double> q2;
    </code>
    queue的基本操作有：
    入队，如例：q.push(x);将x街道队列的末端。
    出队，如例：q.pop(x);弹出队列的第一个元素，注意，并不会返回被弹出的元素的值。
    访问队首元素，如例：q.front(); 即最早被压入队列的元素。
    访问队尾元素，如例：q.back();即最后被压入队列的元素。
    判断队列空，如例:q.empty(); 当队列为空时，返回true.
    访问队列中的元素个数。如例：q.size()
`<code>`
`#include <cstdlib>`
`#include <iostream>`
`#include <queue>`

`using namespace std;`

`int main()`
`{`
    `int e,n,m;`
    `queue<int> q1;`
    `for(int i=0;i<10;i++)`
       `q1.push(i);`
    `if(!q1.empty())`
    `cout<<"dui lie  bu kong\n";`
    `n=q1.size();`
    `cout<<n<<endl;`
    `m=q1.back();`
    `cout<<m<<endl;`
    `for(int j=0;j<n;j++)`
    `{`
       `e=q1.front();`
       `cout<<e<<" ";`
       `q1.pop();`
    `}`
    `cout<<endl;`
    `if(q1.empty())`
    `cout<<"dui lie  bu kong\n";`
    `system("PAUSE");`
    `return 0;`
`}`
`</code>`

