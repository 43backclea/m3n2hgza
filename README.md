## Git算不算程序员的必备技能？ VGOXH8

更新时间：2026-09-15 06:51:26.637

42gqiq.kvb1983.com
40u1aa.ecvyksp.cn
2rj15i.kvb1979.com
487j2t.kvb1996.com
3ct8rt.kvb1992.com
Git算不算程序员的必备技能？
38b4p9.inmolopez.com
3x753d.inmolopez.com
3tjmfb.hoodamath2.com
48iu27.hothairybushes.com
38gxyj.cdroutlet.com
302d0w.hoodamath2.com
2t1v6e.inmolopez.com
3zbkmk.cdroutlet.com
3bwios.hoodamath2.com
在Repository name填入testgit，其他保持默认设置，点击“Create repository”按钮，就成功地创建了一个新的Git仓库：
3gutap.inmolopez.com
2w6x46.kvb1999.com
3i95gf.cdroutlet.com
3vc9v6.hothairybushes.com
3lpzsz.kvb1986.com
Git算不算程序员的必备技能？
2x7or6.hothairybushes.com
4bvkz7.kvb1983.com
首先，登录github上，然后在右上角找到“create a new repo”创建一个新的仓库。如下：
3ueff0.kvb1985.com
3tzteg.kvb1998.com
2wgpjl.kvb1988.com
现在的情景是：我们已经在本地创建了一个Git仓库后，又想在github创建一个Git仓库，并且希望这两个仓库进行远程同步，这样github的仓库可以作为备份，又可以其他人通过该仓库来协作。
45k6d0.kvb1982.com
4a5fyb.kvb1992.com
3chq03.inmolopez.com
3elhdx.inmolopez.com
3ada9t.ecvyksp.cn
如何添加远程库？
3xftfk.cdroutlet.com
3xraum.kvb1991.com
2r41n6.kvb1980.com
2lueb1.inmolopez.com
Git算不算程序员的必备技能？
3jdixa.misturabela.com
点击 Add Key，你就应该可以看到已经添加的key。
3fum47.cdroutlet.com
3e91ji.kvb1996.com
2ra05e.kvb1996.com
Git算不算程序员的必备技能？
3ahy03.inmolopez.com
2svlkx.kvb1998.com
3j68gs.kvb1987.com
第二步：登录github,打开” settings”中的SSH Keys页面，然后点击“Add SSH Key”,填上任意title，在Key文本框里黏贴id_rsa.pub文件的内容。
35on8k.kvb1992.com
2l4iow.ecvyksp.cn
id_rsa是私钥，不能泄露出去，id_rsa.pub是公钥，可以放心地告诉任何人。
3etagq.kvb1983.com
3k7dx8.hongyihualang.cn
3irzvq.kvb1978.com
Git算不算程序员的必备技能？
2v9rtx.hoodamath2.com
2nwwoj.misturabela.com
3vxd6d.hongyihualang.cn
34yaid.ecvyksp.cn
3jkies.kvb1987.com
3vbxd2.inmolopez.com
ssh-keygen -t rsa –C “youremail@example.com”, 由于我本地此前运行过一次，所以本地有，如下所示：
3i29wq.ecvyksp.cn
469rds.hoodamath2.com
49d149.kvb1982.com
4bgmkw.kvb1990.com
第一步：创建SSH Key。在用户主目录下，看看有没有.ssh目录，如果有，再看看这个目录下有没有id_rsa和id_rsa.pub这两个文件，如果有的话，直接跳过此如下命令，如果没有的话，打开命令行，输入如下命令：
37j4tf.kvb1992.com
2uy1pe.kvb1987.com
在了解之前，先注册github账号，由于你的本地Git仓库和github仓库之间的传输是通过SSH加密的，所以需要一点设置：
39noyv.kvb1995.com
3fkg92.kvb1979.com
2z0zj2.cdroutlet.com
2wmu3k.kvb1983.com
五：远程仓库。
3syemy.compasslandconsultants.com
Git算不算程序员的必备技能？
43iyne.misturabela.com
36zg0x.kvb1988.com
2r89vj.kvb1981.com
4iph2d.kvb1980.com
再来看看我们testgit目录，添加了3个文件了。如下所示：
48msug.kvb1988.com
34ywiv.ecvyksp.cn
Git算不算程序员的必备技能？
46i9ee.ecvyksp.cn
可以使用如下命令 git checkout -- b.txt，如下所示：
30e2id.kvb1989.com
只要没有commit之前，如果我想在版本库中恢复此文件如何操作呢？
49hslg.kvb1995.com
Git算不算程序员的必备技能？
2vb30s.hothairybushes.com
如上：一般情况下，可以直接在文件目录中把文件删了，或者使用如上rm命令：rm b.txt ，如果我想彻底从版本库中删掉了此文件的话，可以再执行commit命令 提交掉，现在目录是这样的，
3zypou.kvb1995.com
Git算不算程序员的必备技能？
325igv.kvb1983.com
39bqmd.kvb1985.com
假如我现在版本库testgit目录添加一个文件b.txt,然后提交。如下：
2rta8f.kvb1983.com
2t3hgl.kvb1996.com
34sjyy.kvb1992.com
二：删除文件。
3u0nor.hoodamath2.com
注意：命令git checkout -- readme.txt 中的 -- 很重要，如果没有 -- 的话，那么命令变成创建分支了。
303gkk.kvb1980.com
3q2xrm.kvb1997.com
3m641r.hongyihualang.cn
3a7rk4.inmolopez.com
30axo5.compasslandconsultants.com
Git算不算程序员的必备技能？
2m3o2r.inmolopez.com
3qv1bi.misturabela.com
对于第二种情况，我想我们继续做demo来看下，假如现在我对readme.txt添加一行 内容为6666666666666，我git add 增加到暂存区后，接着添加内容7777777，我想通过撤销命令让其回到暂存区后的状态。如下所示：
3r28x9.inmolopez.com
2.另外一种是readme.txt已经放入暂存区了，接着又作了修改，撤销修改就回到添加暂存区后的状态。
3ijvqq.compasslandconsultants.com
396vu7.compasslandconsultants.com
399vnu.cdroutlet.com
2ycnwl.misturabela.com
1.readme.txt自动修改后，还没有放到暂存区，使用 撤销修改就回到和版本库一模一样的状态。
3lruyy.inmolopez.com
46r2cg.compasslandconsultants.com
命令 git checkout --readme.txt 意思就是，把readme.txt文件在工作区做的修改全部撤销，这里有2种情况，如下：
3qdrkh.kvb1979.com
2rbdix.kvb1993.com
47bj10.cdroutlet.com
Git算不算程序员的必备技能？
3km5ms.kvb1985.com
3wxqlq.hothairybushes.com
32jqbr.kvb1990.com
2vj0rv.kvb1988.com
git checkout -- readme.txt,如下所示：
3lakw6.kvb1995.com
3v1lcp.kvb1998.com
2sak3r.kvb1989.com
2qhulo.kvb1978.com
可以发现，Git会告诉你，git checkout -- file 可以丢弃工作区的修改，如下命令：
3556b6.hoodamath2.com
3hlpix.hoodamath2.com
3jc8mp.kvb1995.com
3iespy.hoodamath2.com
37demo.inmolopez.com
2rdkrl.kvb1988.com
346cte.cdroutlet.com
Git算不算程序员的必备技能？
47d4k5.hongyihualang.cn
但是现在我不想使用上面的2种方法，我想直接想使用撤销命令该如何操作呢？首先在做撤销之前，我们可以先用 git status 查看下当前的状态。如下所示：
40sd9u.kvb1999.com
第二：我可以按以前的方法直接恢复到上一个版本。使用 git reset --hard HEAD^
42j5uy.kvb1981.com
443amt.kvb1978.com
2yg46n.kvb1982.com
第一：如果我知道要删掉那些内容的话，直接手动更改去掉那些需要的文件，然后add添加到暂存区，最后commit掉。
4ehqlf.kvb1996.com
2qzce5.inmolopez.com
3eoqkb.compasslandconsultants.com
3rqyqz.hongyihualang.cn
3vjabx.kvb1999.com
486ojj.kvb1985.com
在我未提交之前，我发现添加5555555555555内容有误，所以我得马上恢复以前的版本，现在我可以有如下几种方法可以做修改：
3jmcqs.compasslandconsultants.com
2zl4yo.misturabela.com
32olrb.kvb1982.com
3zhqx0.misturabela.com
3me85o.kvb1981.com
3c2k3c.inmolopez.com
3slyyj.hoodamath2.com
Git算不算程序员的必备技能？
3zmgbo.kvb1978.com
3vbc0h.misturabela.com
48k871.ecvyksp.cn
3ccbxy.kvb1992.com
485243.kvb1991.com
4f2guh.kvb1983.com
3h09z6.kvb1997.com
2wjaz4.kvb1989.com
比如我现在在readme.txt文件里面增加一行 内容为555555555555，我们先通过命令查看如下：
43pymz.kvb1980.com
2qedv2.kvb1998.com
一：撤销修改：
33ajce.hothairybushes.com
30snj4.kvb1979.com
四：Git撤销修改和删除文件操作。
3rjqyt.ecvyksp.cn
3r8x6w.misturabela.com
Git算不算程序员的必备技能？
2xkebo.hongyihualang.cn
接着我们可以使用git commit一次性提交到分支上，如下：
49keax.kvb1991.com
3009c6.ecvyksp.cn
Git算不算程序员的必备技能？
3rzxtp.kvb1995.com
现在我们先使用git add 命令把2个文件都添加到暂存区中，再使用git status来查看下状态，如下：
3qwfot.kvb1991.com
Git算不算程序员的必备技能？
2twde2.cdroutlet.com
45nacj.kvb1980.com
我们在readme.txt再添加一行内容为4444444，接着在目录下新建一个文件为test.txt 内容为test，我们先用命令 git status来查看下状态，如下：
3qcb53.hongyihualang.cn
3bxsph.kvb1988.com
3tw8zi.compasslandconsultants.com
3wivk4.compasslandconsultants.com
2o1cg3.hothairybushes.com
2z5x7w.kvb1979.com
我们继续使用demo来演示下：
3jge44.hoodamath2.com
3dgmsd.kvb1980.com
2vwytc.inmolopez.com
34ub7g.kvb1997.com
3p6du6.kvb1995.com
37rrre.inmolopez.com
第二步：使用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支上。
2xhq2b.misturabela.com
40q0u0.inmolopez.com
第一步：是使用 git add 把文件添加进去，实际上就是把文件添加到暂存区。
3p2lof.cdroutlet.com
40t1fq.kvb1991.com
2rfo1w.hoodamath2.com
2wap7k.kvb1992.com
我们前面说过使用Git提交文件到版本库有两步：
35huy.compasslandconsultants.com
版本库(Repository)：工作区有一个隐藏目录.git,这个不属于工作区，这是版本库。其中版本库里面存了很多东西，其中最重要的就是stage(暂存区)，还有Git为我们自动创建了第一个分支master,以及指向master的一个指针HEAD。
3pac4q.hothairybushes.com
工作区：就是你在电脑上看到的目录，比如目录下testgit里的文件(.git隐藏目录版本库除外)。或者以后需要再新建的目录文件等等都属于工作区范畴。
37uav7.kvb1979.com
3p90hy.kvb1998.com
2rbpkq.compasslandconsultants.com
三：理解工作区与暂存区的区别？
42yurw.hoodamath2.com
可以看到 目前已经是最新的版本了。
2wlmqg.kvb1999.com
36vkrk.kvb1993.com
Git算不算程序员的必备技能？
3z2sdh.hongyihualang.cn
3ix4eb.kvb1988.com
3cn430.hothairybushes.com
48p1iq.ecvyksp.cn
git reset --hard 6fcfc89来恢复了。演示如下：
44gvwm.kvb1998.com
33x39x.ecvyksp.cn
通过上面的显示我们可以知道，增加内容3333的版本号是 6fcfc89.我们现在可以命令
49cre4.hothairybushes.com
2uhgfc.kvb1978.com
3zh6j5.hoodamath2.com
3ou6yu.kvb1991.com
32uv99.compasslandconsultants.com
Git算不算程序员的必备技能？
4euq6i.kvb1999.com
4gq9em.kvb1992.com
45yyg7.hongyihualang.cn
git reset --hard 版本号 ，但是现在的问题假如我已经关掉过一次命令行或者333内容的版本号我并不知道呢？要如何知道增加3333内容的版本号呢？可以通过如下命令即可获取到版本号：git reflog 演示如下：
3znc24.kvb1990.com
31o3a7.kvb1998.com
我们看到 增加333333 内容我们没有看到了，但是现在我想回退到最新的版本，如：有333333的内容要如何恢复呢？我们可以通过版本号回退，使用命令方法如下：
2rk2b2.kvb1990.com
3x9cel.kvb1998.com
3u6bqj.kvb1988.com
30os17.kvb1978.com
4hnr37.kvb1982.com
Git算不算程序员的必备技能？
3h6tb0.hoodamath2.com
可以看到，内容已经回退到上一个版本了。我们可以继续使用git log 来查看下历史记录信息，如下：
30ic3f.hoodamath2.com
3mmp78.kvb1983.com
40v681.kvb1979.com
Git算不算程序员的必备技能？
3xuo5n.ecvyksp.cn
4fo3hx.kvb1988.com
再来查看下 readme.txt内容如下：通过命令cat readme.txt查看
4a8mlq.kvb1998.com
3fqnxf.compasslandconsultants.com
3ylrqs.kvb1993.com
3ms67q.kvb1999.com
Git算不算程序员的必备技能？
3p0cyi.hoodamath2.com
2vvkxy.ecvyksp.cn
2yd1yo.kvb1985.com
33p5qg.ecvyksp.cn
2phjr8.cdroutlet.com
3i3zpk.kvb1995.com
如果想回退到上一个版本的命令如下操作：
44n9d4.inmolopez.com
Git算不算程序员的必备技能？
314wkj.ecvyksp.cn
2zxsyh.compasslandconsultants.com
现在我想使用版本回退操作，我想把当前的版本回退到上一个版本，要使用什么命令呢？可以使用如下2种命令，第一种是：git reset --hard HEAD^ 那么如果要回退到上上个版本只需把HEAD^ 改成 HEAD^^ 以此类推。那如果要回退到前100个版本的话，使用上面的方法肯定不方便，我们可以使用下面的简便命令操作：git reset --hard HEAD~100 即可。未回退之前的readme.txt内容如下：
2z9or5.kvb1986.com
32qn7l.inmolopez.com
Git算不算程序员的必备技能？
3us6h9.compasslandconsultants.com
git log命令显示从最近到最远的显示日志，我们可以看到最近三次提交，最近的一次是,增加内容为333333.上一次是添加内容222222，第一次默认是 111111.如果嫌上面显示的信息太多的话，我们可以使用命令 git log –pretty=oneline 演示如下：
36q4y6.kvb1978.com
480igz.kvb1980.com
36y1z2.inmolopez.com
2z57y5.kvb1986.com
33tgit.kvb1982.com
Git算不算程序员的必备技能？
3mig64.kvb1986.com
3bk00n.hongyihualang.cn
现在我已经对readme.txt文件做了三次修改了，那么我现在想查看下历史记录，如何查呢？我们现在可以使用命令 git log 演示如下所示：
3wsysk.kvb1995.com
41c48t.kvb1993.com
3a7vep.kvb1987.com
2vbd4r.kvb1986.com
Git算不算程序员的必备技能？
4fefk7.kvb1981.com
内容为33333333333333.继续执行命令如下：
3rtdz4.kvb1979.com
403kuz.hoodamath2.com
如上，我们已经学会了修改文件，现在我继续对readme.txt文件进行修改，再增加一行
2mcpbq.hoodamath2.com
3asi1t.kvb1996.com
3ur8cx.cdroutlet.com
3se18a.kvb1980.com
3zmw3v.kvb1996.com
3ebhsn.kvb1995.com
3vpl8i.kvb1997.com
二：版本回退：
2v5fm0.kvb1979.com
3zew6g.compasslandconsultants.com
Git算不算程序员的必备技能？
4h3btf.kvb1987.com
39df8g.kvb1997.com
3iyc71.hongyihualang.cn
3ym36b.ecvyksp.cn
如下：
4akz0m.kvb1983.com
3glol2.kvb1997.com
知道了对readme.txt文件做了什么修改后，我们可以放心的提交到仓库了，提交修改和提交文件是一样的2步(第一步是git add 第二步是：git commit)。
35wyp4.hoodamath2.com
如上可以看到，readme.txt文件内容从一行11111111改成 二行 添加了一行22222222内容。
48uvl7.compasslandconsultants.com
3hpl8a.kvb1997.com
3ha8mn.kvb1982.com
Git算不算程序员的必备技能？
3wvpxl.misturabela.com
git diff readme.txt 如下：
3bt8gq.cdroutlet.com
2tr6w3.hongyihualang.cn
3afzr9.kvb1982.com
2wafrx.ecvyksp.cn
4hsk3i.kvb1992.com
接下来我想看下readme.txt文件到底改了什么内容，如何查看呢？可以使用如下命令：
3ysks2.kvb1978.com
421mxu.kvb1991.com
40wo2g.misturabela.com
3q1y9h.kvb1996.com
2ylhxl.kvb1996.com
32yo8x.kvb1989.com
3cvj2r.kvb1986.com
上面的命令告诉我们 readme.txt文件已被修改，但是未被提交的修改。
4150h0.compasslandconsultants.com
31eaej.ecvyksp.cn
Git算不算程序员的必备技能？
3ss8am.kvb1988.com
说明没有任何文件未提交，但是我现在继续来改下readme.txt内容，比如我在下面添加一行2222222222内容，继续使用git status来查看下结果，如下：
3zl7cj.hongyihualang.cn
43a43t.kvb1986.com
3nd5me.ecvyksp.cn
2udwfy.misturabela.com
3u0z4k.kvb1985.com
Git算不算程序员的必备技能？
494qyt.cdroutlet.com
38dlbw.misturabela.com
现在我们已经提交了一个readme.txt文件了，我们下面可以通过命令git status来查看是否还有文件未提交，如下：
49nd8b.misturabela.com
Git算不算程序员的必备技能？
493vmy.inmolopez.com
3ww4ja.cdroutlet.com
42vd27.ecvyksp.cn
第二步：用命令 git commit告诉Git，把文件提交到仓库。
3h69kd.kvb1988.com
37xoe5.kvb1989.com
3qfirq.cdroutlet.com
如果和上面一样，没有任何提示，说明已经添加成功了。
351lnk.kvb1978.com
44vm2t.hoodamath2.com
39c9rk.inmolopez.com
37ee3j.kvb1993.com
43oc8a.compasslandconsultants.com
4d9qj4.kvb1988.com
3u6vdj.kvb1993.com
2xgdq4.kvb1983.com
46ruqe.misturabela.com
Git算不算程序员的必备技能？
3tl2g6.misturabela.com
2mjhzz.cdroutlet.com
第一步：使用命令 git add readme.txt添加到暂存区里面去。如下：
3eqvx8.kvb1993.com
4c0629.kvb1983.com
4d6m1s.kvb1993.com
3khre4.hongyihualang.cn
我在版本库testgit目录下新建一个记事本文件 readme.txt 内容如下：11111111
3b6p4a.kvb1995.com
下面先看下demo如下演示：
39j7cz.kvb1992.com
把文件添加到版本库中。首先要明确下，所有的版本控制系统，只能跟踪文本文件的改动，比如txt文件，网页，所有程序的代码等，Git也不列外，版本控制系统可以告诉你每次的改动，但是图片，视频这些二进制文件，虽能也能由版本控制系统管理，但没法跟踪文件的变化，只能把二进制文件每次改动串起来，也就是知道图片从1kb变成2kb，但是到底改了啥，版本控制也不知道。
2spnbz.kvb1979.com

---

# m3n2hgza
Auto-created repository for publishing - 2026-09-15T06:51:20.871Z
