# ti
    <!-- 第一题 -->
    1.  操场上100多人排队，三⼈一组多1人，四⼈一组多2人，五⼈一组多3⼈，共多少人？(118，178)
    <script>
    for(let i=100;i<=200;i++){
        if(i%3==1 && i%4==2 && i%5==3){
            document.write(i)
        }
    } 
    </script>
    <!-- 第二题 -->
    2.  甲、乙、丙、丁四⼈共加⼯零件370个，如果把甲做的个数加10个，⼄做的个数减20个，丙做的个数乘以2，丁做的个数除以2，四人做的零件数正好相等，求甲实际加⼯了多少个零件？(70)
    <script>
        for(let x=0; x<=370;x++){
            if((x-10)+(x+20)+(x/2)+(x*2)==370){
                console.log(x-10)
            }
        }
    </script>
    <!-- 第三题 -->
    3.  从1到500所有自然数中不不含数字4的自然数共有多少个？（324）
    <script>
        let i=0
            for(a=0;a<5;a++){
            for(b=0;b<=9;b++){
            for(c=0;c<=9;c++){
            if(a!=4 && b!=4 && c!=4)
            i++
            }
            }
            }
        document.write(i)
    </script>
    <!-- 第四题 -->
    4.  两个自然数X，Y相除，商3余10，被除数、除数、商、余数的和是163，求被除数、除数。 (115、35)
    <script>
        for(x=1;x<163;x++){
            for(y=1;y<163;y++){
                if(x=y*3+10){
                    if(x+y+3+10==163){
                        document.write(x,y)
                    }
                }
            }
        }
    </script>
    <!-- 第五题 -->
    5.  某数学竞赛中，参赛⼈人数⼤大约在380~450⼈人之间。比赛结果，全体考生的总平均分为76分，男⽣的平均分为75分，女⽣的平均分为80.1分，求男⼥生各有多少人？(328，80)
    <script>
        for(let x=1;x<450;x++){
            for(let y=1;y<450;y++){
                if(75*x+80.1*y==76*(x+y)){
                    if(x+y>380 && x+y<450){
                        console.log(x,y)
                    }
                }
            }
        }
    </script>
    <!-- 第六题 -->
    6.  一个四位数，恰好等于去掉它的首位数字之后所剩的三位数的3倍，这个四位数是多少？(1500)
    <script>
        for(let i=1000;i<=9999;i++){
            x=i%1000;
            if(3*x==i){
                console.log(i)
                }
            }
    </script>
    <!-- 第七题 -->
    7.  有一个两位数，如果在它的前⾯面添一个3，可得到一个三位数；把3添在它的后⾯面，也可以得到一个三位数。这两个三位数相差468，求原来的两位数。（85）
    <script>
        for(let x=10;x<=99;x++){
            if(x+300+468==10*x+3){
                console.log(x)
            }
        }
    </script>
    <!-- 第八题 -->
    8.  一个六位自然数，将其末位上数字7移⾄首位，其余数字依次向右移动一位，得到一个新的六位数，新的六位数是原六位数的4倍，求原数。 (179487)
    <script>
        for(x=10000;x<=999999;x++){
        let y=0
        y=x*10+7
        let z=0
        z=7*100000+x
        if(z==y*4){
            console.log(y)
            }
        }
    </script>
    <!-- 第九题 -->
    9.要在[ ]、[ ]7、[ ]48这三个数中的每个[ ]内各填上1~9中的一个数字，使中间的两位数是左边的一位数和右边的三位数的平均数，求这三个数。（6、77、148）
    <script>
        for(let x=1;x<=9;x++){
            for(let y=1;y<=9;y++){
                for(let z=1;z<=9;z++){
                    if(y*10+7==((x+z*100+48)/2)){
                        console.log(x,y*10+7,z*100+48)
                    }
                }
            }
        } 
    </script>
    <!-- 第十题 -->
    10. 某⼈去购买教材和练习簿,已知教材每本10元，教参每本5元，练习簿每本0.5元，他总共购买了100本，⽤用了100元。问他购买教材、教参和练习簿各多少本？（1、9、90）
    <script>
        for(let x=1;x<10;x++){
            for(let y=1;y<20;y++){
                for(let z=1;z<98;z++){
                    if(x+y+z==100 && x*10+y*5+z*0.5==100){
                        console.log(x,y,z)   
                    }
                }
            }
        }
    </script>
    <!-- 第十一题 -->
    11. 输出四位自然数中各位数字之和为6并且各位数字互不相同的数，并统计个数。（1023、1032、1203、1230、1302、1320、……、3201、3210，18)
    12. 由数字1、2、3、4、5、6六个数字共可组成多少个没有重复数字的四位数，输出这些数据并统计个数。（1234、1235、1236、1243、1245、1246、1253、……、6542、6543，S=360）
    13. 将100元纸币兑换成10元、5元和1元纸币共20张，输出各种兑换法，并统计个数。（4、11，5；8、2、10；S=2）
    <script>
        for(let x=1;x<10;x++){
            for(let y=1;y<20;y++){
                for(let z=1;z<100;z++){
                    if(x+y+z==20 && x*10+y*5+z*1==100){
                        console.log(x,y,z)
                    }
                }
            }
        }
    </script>
