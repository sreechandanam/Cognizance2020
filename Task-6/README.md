<h3 class="code-line" data-line-start=0 data-line-end=1 ><a id="Psudoode_Armstrong_number_0"></a>Psudoode Armstrong number</h3>
<pre><code>BEGIN
    READ num
    INITALIZE sum=0,temp=num,r
        WHILE temp!=0 DO
            r=temp%10
            sum=sum+r*r*r
            temp=temp/10
    END WHILE
    IF sum=num 
          DISPLAY &quot;num is amgstrong number&quot;
    ELSE
          DISPLAY &quot;num is not an amgstrong number&quot;
    END IF 
END</code></pre>
