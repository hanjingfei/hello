# hello world !
## hello beijing !

## 代码块测试 ruby
``` ruby Discover if a number is prime http://www.noulakaz.net/weblog/2007/03/18/a-regular-expression-to-check-for-prime-numbers/ Source Article
class Fixnum
  def prime?
    ('1' * self) !~ /^1?$|^(11+?)\1+$/
  end
end
```
## 代码效果：verilog
```
always @(posedge hclk) begin : ID_MEM_EMPTY
    if(id_wpt != id_rpt)  id_mem_empty <= `TD 0;
    else id_mem_empty <=  `TD 1;
end
```