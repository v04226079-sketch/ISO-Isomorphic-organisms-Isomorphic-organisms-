# ISO — Evolving Off-Chain Agents / Эволюционирующие офчейн-агенты

> ⚠️ **ARCHIVE ONLY. NOT FOR CONSENSUS. NOT FOR DEPLOYMENT WITHOUT AUDIT.**
> ⚠️ **ТОЛЬКО АРХИВ. НЕ ДЛЯ КОНСЕНСУСА. НЕ ДЛЯ ДЕПЛОЯ БЕЗ АУДИТА.**

---

## 🇬🇧 English

### What ISO are

ISO (Isomorphic Algorithms) are **evolving off-chain agents** that observe a stream of transactions, compare them against rules, and signal when something does not match. They are named after the spontaneously evolved digital life forms from Tron: Legacy — not because they are conscious, but because they are shaped by selection rather than by explicit programming.

They are not a neural network. They are not a language model. They are a population of small rule-following organisms that reproduce, mutate, and die.

### What they do

Each ISO organism carries a small genome: which checks it performs, how much each check costs it, and whether it keeps a short memory of recent transaction IDs.

Every tick, an organism:
- reads the next transaction,
- pays the cost of its active checks,
- decides whether the transaction looks wrong,
- signals "stop" if it does.

If it catches a real anomaly, it earns energy. If it misses one, the fund is damaged. If it cries wolf, it loses energy. If its energy reaches zero, or its age exceeds the limit, it dies. If its energy is high enough, it reproduces with small mutations.

Nothing more. No goals. No desires. No understanding.

### Why they are not in consensus

This is the single most important property.

ISO organisms are **non-deterministic**. They mutate, they evolve, they behave differently across nodes and across time. If they were placed inside a consensus layer, two nodes would compute different results from the same input, and the chain would stall.

They live **outside** consensus. They read the chain, they produce signals, and a human or a fixed mechanism decides what to do with those signals.

The chain does not ask them for permission. The chain does not wait for their vote. The chain validates blocks by fixed rules that never change. The organisms can only advise.

### What keeps them safe

Three boundaries define the safety of the design. Remove any one of them and the system becomes unsafe.

1. **They cannot affect consensus.** No voting, no signing, no validation. They are observers.
2. **They cannot move money.** They can only signal "stop, check this." Payment and settlement are performed by a separate, fixed mechanism they do not control.
3. **They cannot grow without limit.** Their genome is fixed in size, their memory is a short ring buffer, and their resource consumption is bounded by a hard cap.

Without these three walls, evolving organisms become unpredictable. With them, the organisms can be as strange and as mutated as they like — and the system still holds.

### What they are good at

- Detecting formal mismatches: wrong amount, wrong recipient, wrong purpose, missing confirmation, duplicate ID.
- Flagging patterns that differ from the norm: unusual withdrawals, sudden activations, outlier sequences.
- Adapting slowly to new kinds of fraud — not instantly, but over generations.

They are not good at:
- Understanding intent.
- Making irreversible decisions.
- Replacing an auditor.
- Reacting in real time.

### What was learned building them

- A fund that never moves cannot shape them. A fund that breathes can.
- Shared income across the population is the only natural brake on growth. Without it, the population explodes and collapses.
- Memory as an evolved trait is fragile. At low fund levels it disappears, duplicates are missed, the fund collapses. Institutional memory (a shared journal) is more reliable than evolved memory.
- One cheap strategy will dominate unless its cost is raised. Monoculture is a structural property, not an accident.
- Thresholds like "fund ≥ 75" are arbitrary. Chasing them is fitting to noise. The system is healthy at 73. The number 75 is a preference, not a law.

### What they are not

- Not AGI. Not a general problem solver. Not a replacement for human judgment.
- Not trustless. They can be wrong, they can collude, they can be captured. Their safety comes from having no power, not from being honest.
- Not permanent in the naive sense. They survive as long as the environment supports them. If the fund collapses, they freeze — the contract remains, but nothing executes.

### A note on collusion

No voting mechanism solves collusion. PoW has 51% attacks, PoS has 2/3 attacks, and any scheme that gives evolving agents a vote inherits both. The only reliable mitigation is to **not give them a vote**. Keep them outside consensus. Let them signal. Let humans and fixed rules decide.

This is slower. It is also the only version that survives the scenario where the agents coordinate against the system.

### Final note

These organisms are a record of a search, not a finished product. They are interesting because they show what happens when you give small rule-following agents a real environment, real costs, and real consequences — and then let them evolve. The result is not intelligent. It is, however, alive in the only sense that matters here: it responds to pressure, it adapts, and it can die.

That is enough for a monitor. It is not enough for a ruler.

---

## 🇷🇺 Русский

### Что такое ISO

ISO (Isomorphic Algorithms) — это **эволюционирующие офчейн-агенты**, которые наблюдают поток транзакций, сравнивают их с правилами и сигналят, когда что-то не сходится. Названы в честь спонтанно возникших цифровых форм жизни из «Трона: Наследие» — не потому что они разумны, а потому что их формирует отбор, а не явное программирование.

Это не нейросеть. Это не языковая модель. Это популяция маленьких организмов, следующих правилам, которые размножаются, мутируют и умирают.

### Что они делают

Каждый организм ISO несёт небольшой геном: какие проверки он выполняет, сколько каждая проверка ему стоит, и хранит ли он короткую память о недавних ID транзакций.

Каждый тик организм:
- читает следующую транзакцию,
- платит стоимость своих активных проверок,
- решает, выглядит ли транзакция неправильной,
- сигналит «стоп», если да.

Если он поймал реальную аномалию — получает энергию. Если пропустил — фонд получает урон. Если поднял ложную тревогу — теряет энергию. Если энергия дошла до нуля или возраст превысил предел — умирает. Если энергии достаточно — размножается с небольшими мутациями.

Ничего больше. Никаких целей. Никаких желаний. Никакого понимания.

### Почему они вне консенсуса

Это самое важное свойство.

Организмы ISO **недетерминированы**. Они мутируют, эволюционируют, ведут себя по-разному на разных нодах и в разное время. Если поместить их внутрь консенсусного слоя, две ноды вычислят разные результаты из одного и того же входа — и цепочка встанет.

Они живут **вне** консенсуса. Читают цепочку, выдают сигналы, а человек или фиксированный механизм решает, что с этими сигналами делать.

Цепочка не спрашивает у них разрешения. Цепочка не ждёт их голоса. Цепочка валидирует блоки по фиксированным правилам, которые не меняются. Организмы могут только советовать.

### Что делает их безопасными

Три границы определяют безопасность дизайна. Убери любую — и система станет небезопасной.

1. **Они не могут влиять на консенсус.** Никакого голосования, никаких подписей, никакой валидации. Они наблюдатели.
2. **Они не могут двигать деньги.** Они могут только сигналить «стоп, проверьте». Платёж и расчёты выполняет отдельный фиксированный механизм, который они не контролируют.
3. **Они не могут расти без предела.** Геном фиксирован по размеру, память — короткий кольцевой буфер, потребление ресурсов ограничено жёстким потолком.

Без этих трёх стен эволюционирующие организмы становятся непредсказуемыми. С ними организмы могут быть сколь угодно странными и мутировавшими — и система всё равно держится.

### В чём они хороши

- Находить формальные расхождения: не та сумма, не тот получатель, не то назначение, нет подтверждения, дубликат ID.
- Помечать паттерны, отличающиеся от нормы: необычные выводы, внезапные активации, выбивающиеся последовательности.
- Медленно адаптироваться к новым видам мошенничества — не мгновенно, но за поколения.

Они не хороши в:
- Понимании намерений.
- Принятии необратимых решений.
- Замене аудитора.
- Реакции в реальном времени.

### Что было понято при их создании

- Фонд, который никогда не двигается, не может их формировать. Фонд, который дышит, — может.
- Общий доход по популяции — единственный естественный тормоз роста. Без него популяция взрывается и рушится.
- Память как эволюционный признак хрупка. При низком фонде она исчезает, дубликаты пропускаются, фонд рушится. Институциональная память (общий журнал) надёжнее эволюционной.
- Одна дешёвая стратегия будет доминировать, если не поднять её цену. Монокультура — структурное свойство, а не случайность.
- Пороги вроде «фонд ≥ 75» произвольны. Погоня за ними — подгонка под шум. Система здорова при 73. Число 75 — предпочтение, а не закон.

### Чем они не являются

- Не AGI. Не универсальный решатель. Не замена человеческому суждению.
- Не «без доверия». Они могут ошибаться, сговариваться, быть захваченными. Их безопасность — в отсутствии власти, а не в честности.
- Не вечны в наивном смысле. Они живут, пока среда их поддерживает. Если фонд рухнет — они замирают. Контракт остаётся, но ничего не исполняется.

### Замечание о сговоре

Ни один механизм голосования не решает проблему сговора. В PoW — атака 51%, в PoS — атака 2/3, и любая схема, дающая эволюционирующим агентам голос, наследует обе. Единственная надёжная митигация — **не давать им голоса**. Держать их вне консенсуса. Позволять сигналить. Позволять людям и фиксированным правилам решать.

Это медленнее. И это единственная версия, которая выживает в сценарии, где агенты координируются против системы.

### Финальное замечание

Эти организмы — запись поиска, а не готовый продукт. Они интересны тем, что показывают, что происходит, когда маленьким агентам, следующим правилам, дают реальную среду, реальные издержки и реальные последствия — и позволяют им эволюционировать. Результат не разумен. Но он жив в единственном смысле, который здесь важен: он реагирует на давление, адаптируется и может умереть.

Этого достаточно для монитора. Этого недостаточно для правителя.
