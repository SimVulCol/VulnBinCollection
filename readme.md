Our dataset is composed of three parts: vul, tpcs-s, and tpcs-l.

 In the vul part, there are 10 libraries containing a total of 100 CVE vulnerabilities. 

<img src="C:\Users\78621\AppData\Roaming\Typora\typora-user-images\image-20240612175839003.png" alt="image-20240612175839003" style="zoom:50%;" /><img src="C:\Users\78621\AppData\Roaming\Typora\typora-user-images\image-20240612175950916.png" alt="image-20240612175950916" style="zoom:50%;" />

Each vulnerability consists of five types of data: original (including multiple architectures, compilers, and optimizations), ollvm (obfuscated using the ollvm obfuscator), tigress (obfuscated using the Tigress obfuscator), bintuner (created using the Bintuner tool), and patch (the patched version of the vulnerability).

<img src="C:\Users\78621\AppData\Roaming\Typora\typora-user-images\image-20240612180015294.png" alt="image-20240612180015294" style="zoom:50%;" />

<img src="C:\Users\78621\AppData\Roaming\Typora\typora-user-images\image-20240612180031823.png" alt="image-20240612180031823" style="zoom:50%;" />

tpcs-s与tpcs-l作为不同大小搜索池，他们均在gcc-x86-O2的情境下进行比制作

<img src="C:\Users\78621\AppData\Roaming\Typora\typora-user-images\image-20240612180249849.png" alt="image-20240612180249849" style="zoom:50%;" />