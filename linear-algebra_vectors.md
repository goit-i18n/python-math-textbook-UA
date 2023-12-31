---
sidebar_position: 4
---

import Figure from '@components/Figure'

import Formula from '@components/Formula'

import Highlight from '@components/Highlight'

import useBaseUrl from '@docusaurus/useBaseUrl';

# Вектори

Узагальнимо вивчені зі шкільного курсу геометрії дані про вектори. Відомо, що якщо на площині задана прямокутна декартова система координат, то кожна точка $P$ площини однозначно характеризується двома числами $(x, y)$ – _координатами точки_ $P$.

<Figure description="Рис. 1"> 
<img src={useBaseUrl("/img/module-01/pic01.png")} /> 
</Figure>

Аналогічно кожній точці $P$ тривимірного простору (рис. 2) у заданій системі координат відповідає впорядкована трійка чисел $(x, y, z)$, яка називається _координатами точки_ $P$.

<Figure description="Рис. 2"> 
<img src={useBaseUrl("/img/module-01/pic02.png")} /> 
</Figure>

При розв’язанні різних задач доводиться розглядати _спрямований відрізок_, тобто безліч точок, що лежать між точками $A$ і $B$ прямою зі вказаним напрямком

<Figure description="Рис. 3"> 
<img src={useBaseUrl("/img/module-01/pic03.png")} /> 
</Figure>

Напрямок такого відрізка прийнято визначати порядком задання точок $A$ і $B$: позначають через $\overrightarrow{AB}$ спрямований відрізок з початком $A$ і кінцем $B$, спрямований від початку $A$ і кінцю $B$. При цьому зручно не розрізняти між собою два будь-які спрямовані відрізки, якщо вони лежать на паралельних прямих, спрямованих в один бік і мають однакові довжини, оскільки вони як з фізичної, так і з геометричної точки зору позначають одне й те саме.

_Вектором_ називають спрямований відрізок $\overrightarrow{AB}$. Позначають вектор так само, як і спрямований відрізок $\overrightarrow{AB}$ або однією малою літерою $\vec{a}$. _Нульовим вектором_ називають вектор, у якого початок і кінець збігаються, позначення $\vec{0}$ або просто $0$.

Відстань між початком та кінцем вектора називається його _довжиною_ (а також _модулем_ вектора) і позначається $\lvert\overrightarrow{AB}\rvert$ або $|\vec{a}|$. Вектор, довжина якого дорівнює одиниці, називається _одиничним вектором_.

Вектори називають _колінеарними_, якщо вони розташовані на одній прямій або на паралельних прямих.

<Figure description="Рис. 4"> 
<img src={useBaseUrl("/img/module-01/pic04.png")} /> 
</Figure>

Вектори називають _компланарними_, якщо існує площина, якій вони паралельні.

<Figure description="Рис. 5"> 
<img src={useBaseUrl("/img/module-01/pic05.png")} /> 
</Figure>

Два вектори $\overrightarrow{AB}$ і $\overrightarrow{OC}$ будемо називати _рівними_, якщо вони колінеарні, однаково спрямовані та мають рівні модулі. Якщо спрямований відрізок $\overrightarrow{AB}$ перенести паралельно самому собі, то, очевидно, вийде спрямований відрізок, рівний вихідному (рис. 3). Усякий спрямований відрізок $\overrightarrow{AB}$ можна перенести паралельно самому собі так, щоб його початок збігався з початком координат. Зрозуміло, що вектору $\overrightarrow{AB}$ відповідає один і тільки один спрямований відрізок $\overrightarrow{OC}$ з початком у початку координат.

_Координатами вектора_ $\overrightarrow{AB}$ називаються три числа $(x, y, z)$ – координати точки $C$. Вектор з координатами $(x, y, z)$ прийнято позначати $\overrightarrow{AB}=(x, y, z)$. При цьому числа $(x, y, z)$ називають
_проєкціями вектора_ на відповідній осі координат.

Очевидно, що якщо $\overrightarrow{AB}=\overrightarrow{OC}=(x, y, z)$, то його модуль знаходиться за формулою

$|\overrightarrow{AB}|=|\overrightarrow{OC}|=\sqrt{x^2+y^2+z^2}$

_Напрямок вектора_ визначається кутами, які він складає з позитивними напрямками відповідних осей: з віссю $Ox$ – $\angle\alpha$, з $Oy$ – $\angle\beta$ , з $Oz$ – $\angle\gamma$ . Косинуси цих кутів називають напрямними косинусами вектора.
<Figure description="Рис. 6"> 
<img src={useBaseUrl("/img/module-01/pic06.png")} /> 
</Figure>

<Highlight color="#F4F6F6">

**Приклад 1**

Заданий двовимірний вектор $\vec{a}=(x, y)$. Знайти кути, утворені цим вектором з позитивним напрямком відповідних осей координат і встановити залежність між напрямними косинусами цього вектора.

**Розв’язання**

Знаходимо модуль вектора $\overrightarrow{OC}=\vec{a}$

$|\vec{a}|=\sqrt{x^2+y^2}$

З $\triangle CNO$ і $\triangle CMO$ (рис. 7) відповідно знаходимо

<Figure description="Рис. 7"> 
<img src={useBaseUrl("/img/module-01/pic07.png")} /> 
</Figure>

$\cos\alpha = \cfrac{x}{|\vec{a}|}$ $\cos\beta = \cfrac{y}{|\vec{a}|}$

Тоді

$\cos^2\alpha + \cos^2\beta = \left(\cfrac{x}{|\vec{a}|}\right)^2 +  \left(\cfrac{y}{|\vec{a}|}\right)^2 = \cfrac{x^2 + y^2}{|\vec{a}|^2}$

і таким чином залежність між напрямними косинусами двовимірного вектора запишеться

$\cos^2\alpha + \cos^2\beta = 1$

У випадку тривимірного вектора ця залежність має вигляд

$\cos^2\alpha + \cos^2\beta + \cos^2\gamma = 1$

</Highlight>

Якщо точка $A$ має координати $(x_1, y_1, z_1)$, а точка $B$ координати $(x_2, y_2, z_2)$, то вектор $\overrightarrow{AB}$ має координати $(x_2 - x_1, y_2 - y_1, z_2 - z_1)$ (див. рис.8).
<Figure description="Рис. 8"> 
<img src={useBaseUrl("/img/module-01/pic08.png")} /> 
</Figure>

_Сумою векторів_ $\overrightarrow{AB}$ і $\overrightarrow{CD}$ називається третій вектор $\overrightarrow{AD}$, який отримується за _правилом трикутника_: вектори, що додаються, переносяться паралельно самим собі так, щоб початок другого вектора збігся з кінцем першого; тоді спрямований відрізок, що з'єднує початок першого вектора з кінцем другого, і є $\overrightarrow{AD}=\overrightarrow{AB}+\overrightarrow{CD}$.

<Figure description="Рис. 9"> 
<img src={useBaseUrl("/img/module-01/pic09.png")} /> 
</Figure>

З визначення дії додавання випливає, що:

1. $\vec{a} + \vec{b} = \vec{b} + \vec{a}$ (властивість переміщення);
2. $(\vec{a} + \vec{b}) + \vec{c} = \vec{a} + (\vec{b} + \vec{c})$ (властивість сполучності).

Для кожного вектора $\vec{a}=\overrightarrow{OA}$ існує _протилежний вектор_ $-\vec{a}=\overrightarrow{OA'}$, який має таку саму довжину, але протилежний напрямок. Очевидно, що $\vec{a} + (-\vec{a})=0$, де $0$ &mdash; нуль-вектор.

<Figure description="Рис. 10"> 
<img src={useBaseUrl("/img/module-01/pic10.png")} /> 
</Figure>

З визначення суми векторів випливає _правило паралелограма_ для складання двох векторів – сума двох векторів $\overrightarrow{OA}=\vec{a}$ і $\overrightarrow{OB}=\vec{b}$, зведених до спільного початку $0$, являє собою діагональ паралелограма $OACB$, побудованого на векторах, що додаються.

<Figure description="Рис. 11"> 
<img src={useBaseUrl("/img/module-01/pic11.png")} /> 
</Figure>

Аналогічно визначається сума кількох векторів 
$\vec{a_1},\vec{a_2},\vec{a_3},...,\vec{a_n}$ . Будуються вектори
$\vec{a_1}'=\vec{a_1},\vec{a_2}'=\vec{a_2},...,\vec{a_n}'=\vec{a_n}$ так, щоб початок вектора $\vec{a_2}'$ збігся з кінцем вектора $\vec{a_1}'$ і так далі, початок вектора $\vec{a_n}'$ збігався з кінцем вектора $\vec{a}_{n-1}'$. Тоді вектор $\vec{S}$, початок якого збігається з початком вектора $\vec{a_1}'$, а кінець з кінцем вектора $\vec{a_n}'$ будемо
називати сумою векторів $\vec{a_1}',\vec{a_2}',\vec{a_3}',...,\vec{a_n}'$.
<Figure description="Рис. 12"> 
<img src={useBaseUrl("/img/module-01/pic12.png")} /> 
</Figure>

Віднімання векторів визначається як операція, зворотна до додавання. Різницею векторів $\vec{a}$ і $\vec{b}$ називається вектор $\vec{a} – \vec{b}$, який у сумі з вектором $\vec{b}$ дає вектор $\vec{a}$. У паралелограмі, побудованому на даних векторах $\vec{a}$ і $\vec{b}$ їх різницею є відповідно спрямована друга діагональ паралелограма.

<Figure description="Рис. 13"> 
<img src={useBaseUrl("/img/module-01/pic13.png")} /> 
</Figure>

Для будь-яких векторів $\vec{a}$ і $\vec{b}$ справедлива _нерівність трикутника_

$|\vec{a}+\vec{b}| \leq |\vec{a}| + |\vec{b}|$

Вона виходить із того, що сума двох сторін трикутника більше третьої сторони (рис. 14).

<Figure description="Рис. 14"> 
<img src={useBaseUrl("/img/module-01/pic14.png")} /> 
</Figure>

Добутком вектора $\vec{a}$ на число $k$ називається вектор $k\vec{a}$, модуль якого рівний добутку модуля вектора $\vec{a}$ на модуль числа $k$, а напрямок збігається з напрямком вектора $\vec{a}$, якщо $k>0$, і протилежно напрямку вектора $\vec{a}$, якщо $k<0$. При $k=0$ або $\vec{a}=0$ рахують $k\vec{a}=0$.

<Figure description="Рис. 15"> 
<img src={useBaseUrl("/img/module-01/pic15.png")} /> 
</Figure>

Якщо вектори $\vec{a}$ і $\vec{b}$ колінеарні і не рівні нулю, то $\vec{a}=k\vec{b}$, $\vec{b}=\cfrac{1}{k}\vec{a}$.

Ця операція має властивості:

1. $\lambda(\mu\vec{a}) = (\lambda\mu)\vec{a}$ (сполучність);
2. $(\lambda + \mu)\vec{a} = \lambda\vec{a} + \mu\vec{a}$ (розподільність відносно чисел);
3. $\lambda(\vec{a} + \vec{b}) = \lambda\vec{a} + \lambda\vec{b}$ (розподільність відносно векторів).

_Проєкцією точки_ $A$ на вісь $l$ називається основа $A'$ перпендикуляра $AA'$, опущеного з точки $A$ на цю вісь.

<Figure description="Рис. 16"> 
<img src={useBaseUrl("/img/module-01/pic16.png")} /> 
</Figure>

Під _компонентою_ (_складовою_) вектора $\vec{a}=\overrightarrow{AB}$ відносно осі $l$ (рис. 16) розуміється вектор $\vec{a'}=\overrightarrow{A'B'}$, початок якого є $A'$ проєкція на вісь $l$ початку вектора $\vec{a}$, а кінець якого $B'$ є проєкція на вісь $l$ кінця $B$ цього вектора.

Під проєкцією вектора $\vec{a}$ на вісь $l$ розуміється скаляр $a_1=\pm|\overrightarrow{A'B'}|$, рівний модулю його компоненти $\vec{a'}$ відносно осі $l$, взятої зі знаком плюс, якщо напрямок компоненти збігається з напрямком осі $l$, і зі знаком мінус, якщо напрямок компоненти протилежний напрямку осі $l$. Зауважимо, що якщо $\vec{e}$ – одиничний вектор осі $l$, то для компоненти $\vec{a'}$ справедлива рівність

$\vec{a'}=a_1\vec{e}$

Нехай вектор $\vec{a}=(a_x,a_y,a_z)$ заданий своїми проєкціями на осі координат $O_x,O_y,O_z$.

Побудуємо паралелепіпед (рис. 17), діагоналлю якого є вектор $\vec{a}$, а ребрами слугують його компоненти $\vec{a_1}$, $\vec{a_2}$, $\vec{a_3}$ відносно координатних осей. Маємо розкладання

<Formula description="(1)">

$\vec{a}=\vec{a_1}+\vec{a_2}+\vec{a_3}$

</Formula>

<Figure description="Рис. 17"> 
<img src={useBaseUrl("/img/module-01/pic17.png")} /> 
</Figure>

Якщо ввести одиничні вектори $\vec{i}$, $\vec{j}$, $\vec{k}$ спрямовані по осях координат, то на основі $\vec{a'}=a_1\vec{e}$ будемо мати

$\vec{a_1}=a_x\vec{i}$, $\vec{a_2}=a_y\vec{j}$, $\vec{a_3}=a_z\vec{k}$.

Підставляючи ці вирази в рівність (1), отримуємо координатну форму вектора

$\vec{a}=a_x\vec{i}+a_y\vec{j}+a_z\vec{k}$

Якщо $\vec{b}=(b_x,b_y,b_z)$, то аналогічно

$\vec{b}=b_x\vec{i} + b_y\vec{j} + b_z\vec{k}$

Тепер розглянуті вище лінійні операції над векторами можна записати в координатній формі:

$\lambda\vec{a}=\lambda a_x\vec{i} + \lambda a_y\vec{j} + \lambda a_z\vec{k}$

або

$\lambda\vec{a}=(\lambda a_x, \lambda a_y, \lambda a_z)$

тобто при множенні вектора на скаляр координати вектора множаться на цей скаляр;

$\vec{a}\pm\vec{b}=(a_x \pm b_x)\vec{i} + (a_y \pm b_y)\vec{j} + (a_z \pm b_z)\vec{k}$

або

$\vec{a}\pm\vec{b}=(a_x \pm b_x, a_y \pm b_y, a_z \pm b_z)$

тобто при додаванні (або відніманні) векторів їх однойменні координати додаються (або віднімаються).
