# S_PI_D_ERMAN


这个版本更改了neirong.html 为了防止全站被k，所以特地给search xiazai 这些加了目录innovation

并且对应的filter也改进了一下，为了防止原站和劫持后的站差距过大，所以在spider访问非innovation目录的时候(即访问原来网站的uri时候，给可能的回访蜘蛛做准备)网页与原来网页差距过大，而导致站被k掉



####非全站劫持版本1.1 2023/12/09

把内容(neirong.html)里的 《a href="http://xxx/innovation/kAWads.html"》改成了 《.a href="./kAWads.html"》原因是防止蜘蛛认为带host的href是外联(之所以不带innovation了是因为neirong.html肯定是在./innovation目录下的)
还改了下image js 这些路径 因为有/innovation目录的远古所以，这些都要加上../
