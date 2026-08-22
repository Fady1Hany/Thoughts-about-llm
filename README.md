> **A Note :**
I used AI to help with the English phrasing and translation of this work because English is not my first language. The ideas themselves are entirely my own personal thoughts and hypotheses. I used AI primarily to express those ideas more clearly and naturally in English, so that they could be accessible to a wider audience. I also used AI to help incorporate relevant sources. The underlying ideas and arguments are mine; the wording, English phrasing, translation, and assistance with sources were supported by AI.

## Thoughts-about-LLMs and AI. Just a few thoughts 

---

> At the simplest level, an LLM is trained on enormous amounts of data—code, articles, books, novels, news, and vast portions of the internet. Its fundamental training objective is remarkably simple: predict the next token. Given everything that came before, what token is most likely to come next?
That sounds almost trivial. And in one sense, it is. The model is not given a dictionary of meanings and told to understand what a sentence means. It is not explicitly taught, word by word, what the world is or what a human intention is. It learns statistical patterns from the data and uses those patterns to predict what comes next.
But there is an important complication: to become extremely good at predicting the next token, the model ends up learning far more than surface-level word associations. Its internal representations can encode concepts, relationships, patterns, and even forms of reasoning. So it would be wrong to say that an LLM simply looks at the previous word and guesses the next one.
It predicts the next token—but in doing so, it can build surprisingly rich internal representations of the information it has seen. but without understanding any single word ... so I don't think this is intelligent at any form of intelligent
but it's a great tool it can help in multiple fields
----

## and for that I set out to solve energy problem. that we need to solve in order to achieve progress in creating more powerful language models, or even if we manage to create true intelligence


## ( From the Arc Reactor to biology )

Every conversation about the AI revolution eventually becomes a conversation about models. Parameter counts, architectures, release dates. The more I read, the more I became convinced that the real question was buried underneath all of that noise:

Where will the electricity come from?

Chips are manufactured and clusters are built, but a genuine revolution—in the full sense of the word—requires energy that is vast, cheap, reliable, and scalable. So I decided to walk the problem from beginning to end, without a map, and see where the roads break and where an exit might be hiding.

The journey started with a fictional reactor in the chest of a comic-book hero, passed through nuclear plants, thermodynamics, and a molecule called ATP, and ended somewhere I never expected to go

This is the story in the order I walked it—dead ends included. Because sometimes the dead end is the map.

## 1. A Reactor the Size of a Fist


The goal was simple. If the revolution needs a new power source, start from the closest thing to that dream: the Arc Reactor, Tony Stark's palm-sized power source that runs a full suit, rockets, weapons, and the computational machinery of a superhero.

The question I began with was not whether we could build one.

It was whether the Arc Reactor is fictional because of engineering, or because of physics.

The difference matters enormously.

One is a matter of time.

The other is a matter of the universe.

To answer it, I had to step back and ask something that initially sounded almost naive.

## 2. What Electricity Actually Is


Electricity is not a substance that we manufacture. In an electrical system, energy is transferred through electric and magnetic fields and converted into forms we can use; moving charges are one important part of the picture.

That immediately pushed the question one level deeper:

What is energy? Can we create it?

The answer established by nineteenth-century thermodynamics is no. Energy is conserved. It can be transferred and transformed, but never created from nothing.

Einstein contributed something different and extraordinary:

E = mc².

Mass itself is a form of energy. In fission, roughly a tenth of one percent of the fuel's mass becomes energy. In some fusion reactions, the mass difference is larger. But none of this violates conservation.

It expands the ledger.

The energy was not created. It was already there, encoded in mass.

That gave me the first solid conclusion of the journey:

There is no creation, only conversion.

Any future "miracle" energy source will still be a conversion system. The real questions are energy density, efficiency, controllability, scalability—and what happens to everything that cannot be turned into useful work.

With that lens, I went back to the reactor.

## 3. The Nuclear Plant Is a Steam Engine in Disguise


What does the fictional reactor appear to do? Produce enormous amounts of energy from a compact source and somehow convert it directly into usable power.

And here I realized that the genius of the fiction isn't simply miniaturization.

It is that the fiction quietly skips some of the hardest parts of the real energy-conversion chain.

A conventional nuclear plant is, in broad terms, a very sophisticated heat engine. Fission releases energy as heat. The heat boils water. The steam spins a turbine. The turbine drives a generator. The generator produces electricity.

Nuclear → heat → steam → motion → electricity.

At every stage, thermodynamics puts limits on how much of the original energy can become useful output. Waste heat is not an engineering accident. It is a consequence of the physics of heat engines.

So why is nuclear power so powerful? Not because its turbines are magical—because nuclear fuel has an energy density nothing else in civilian use approaches.

Fully fissioned, a single kilogram of uranium-235 releases on the order of 8×10¹³ joules. A kilogram of water falling a hundred meters delivers about a thousand joules.

A factor of roughly ten billion.

Hydropower is capped by geography—by how much water and how much height the planet happens to offer. Nuclear fuel packs the energy of a small war into a mass you could hold in one hand.

Which made the question more interesting:

If the energy density is that high, why can't we build the reactor in a backpack?

## 4. Three Walls—and Where Marvel Cheats


## The first wall is heat.

High power density means high heat flux. The more energy you extract from a small volume, the harder it becomes to move the resulting heat somewhere else. Cooling needs surface area, mass, pumps, radiators, or some combination of them. Cooling does not shrink.

## The second wall—and arguably the brutal one—is radiation.

Neutrons are best stopped by hydrogen-rich materials. Gamma rays are best attenuated by dense, heavy ones. No thin, light material blocks both. Real radiation shielding is massive not because engineers are unimaginative, but because the mass is part of the physics.

## The third wall is the reactor as a system.

A reactor is not a fuel source. It is fuel, control, shielding, cooling, containment, instrumentation, safety systems, and everything required to keep those pieces operating together. Even when engineers make reactors smaller, those physical requirements do not disappear—they just get packed more tightly.

And then there is Marvel.

For fun, I traced the fiction back to its sources: across decades of comics, Marvel never names the material shielding Tony from his own reactor. It doesn't exist. The "new element" in Iron Man 2 is a plot device that solves his palladium poisoning—not radiation. The fiction hand-waves precisely where reality is hardest.

Fusion does not currently rescue us either.

In 2022, the National Ignition Facility achieved fusion ignition: 3.15 megajoules of fusion energy out, against 2.05 megajoules of laser energy delivered to the target. A genuine scientific milestone. But the laser drew roughly 300 megajoules from the grid to deliver those 2.05.

That distinction matters. We have demonstrated pieces of the physics. We have not built a compact, economical fusion plant that sends net electricity to the grid.

Verdict: an Arc-Reactor-like power source is not an engineering project waiting for one clever invention. It would require breakthroughs across several coupled problems at once. Road one: closed, for now.

So I turned to the second road.

## 5. The Pivot: From Supply to Demand ( software ( llm ) or hardware )


The goal had never really been "build a reactor."

The goal was to remove the energy bottleneck.

If generation is locked, invert the problem: what if we simply needed less? The same intelligence at a fraction of the compute dissolves the bottleneck from the other side, without building anything.

## Hardware 

Future Hardware Developments

There is already strong evidence that AI hardware is rapidly evolving toward much greater energy efficiency, particularly for running large models at inference time. This is not merely a theoretical possibility. Major companies are increasingly designing specialized AI accelerators around performance-per-watt, memory efficiency, and reducing the cost of moving data between computing units.

Google provides a particularly clear example of this trend. In 2025, Google introduced Ironwood, its seventh-generation Tensor Processing Unit (TPU), specifically designed for large-scale AI inference. Google reported that Ironwood provides approximately 2× the performance per watt of its previous-generation Trillium TPU and nearly 30× the power efficiency of its first Cloud TPU from 2018. Ironwood also increased memory capacity and bandwidth substantially, which is important because moving model parameters between memory and compute units can represent a significant part of the energy cost of AI workloads.

The progress has continued. In April 2026, Google announced its eighth-generation TPUs, TPU 8t and TPU 8i, with TPU 8i specifically optimized for inference. Google states that both chips provide up to 2× better performance per watt than Ironwood, while TPU 8i is designed to provide low-latency inference at very large scale. Google also reports that its TPU 8 architecture can connect thousands of accelerators into a single system with very large shared high-bandwidth memory, allowing increasingly large AI models to be processed efficiently.

This progression is significant because the objective is no longer simply to make AI models faster. The industry is increasingly optimizing the entire hardware and software stack to obtain more useful computation and more generated tokens for every unit of electricity consumed. Google reports that its data centers now deliver approximately six times more computing power per unit of electricity than they did five years ago, demonstrating that efficiency improvements are occurring at both the chip and data-center levels.

Therefore, although today's large AI models still require substantial amounts of energy, current hardware trends provide a strong reason to expect their energy requirements per unit of computation to continue decreasing. If this trajectory continues, future generations of specialized AI chips could make it possible to run increasingly capable and larger models within dramatically smaller energy budgets than would be required by today's hardware.

## software 

This led to another question that became impossible to ignore: how much of the remarkable efficiency and low cost of recent Chinese AI models is genuinely the result of new algorithmic advances, and how much comes from distillation ?

The answer is more complicated than the popular arguments suggest.

Knowledge distillation is not an exotic loophole. It is a standard technique, known since Hinton's 2015 paper: a smaller "student" model learns from the outputs or behavior of a larger "teacher," and variants of the idea run through modern AI development.

and Whether this is true or false . the existence of distillation techniques is not, by itself, evidence that a model was simply copied. Building a competitive foundation model still requires enormous quantities of diverse data, optimization, compute, and engineering—and public evidence is rarely sufficient to establish exactly how any particular model was trained.

But the deeper question is more interesting:

To what extent can the cost of achieving a given level of intelligence be reduced through better algorithms, distillation, compression, and hardware—without sacrificing the intelligence itself?

There is no known general algorithm today that gives us an order-of-magnitude reduction in compute while preserving the same level of general intelligence.

The door exists.

We just cannot see the handle.

And that raised the most exciting question of the entire journey.

## 6. Can AI Find the Algorithm Itself?


If the decisive algorithm does not exist, what happens if we ask AI to find it?

This is no longer science fiction.

At the edges of computing, it has already happened:

AlphaDev discovered faster sorting routines and had them merged into widely used C++ libraries—algorithms written by a machine, now running on millions of devices.

AlphaTensor found matrix-multiplication algorithms beating human records that had stood for decades—and matrix multiplication is the core operation of neural networks themselves.

AlphaChip generates chip layouts that ship in real production hardware.

AlphaEvolve (2025) went further: it improved the best known algorithm for 4×4 complex matrix multiplication—the first improvement on that front in decades—and by optimizing Google's own datacenter scheduling, it recovered roughly 0.7% of the company's total compute. An AI system, recovering energy and silicon, by rearranging how we use them.

But the gap is glaring.

All of these successes live at the edges of the intelligence stack: sorting, scheduling, matrix multiplication, chip layout, infrastructure.

The center is harder.

We do not yet have an AI system that has discovered a fundamentally superior training paradigm for large language models—one that makes today's dominant approach obsolete while requiring dramatically less computation.

so I back to the electricity problem but I thought about extraordinary autonomous energy system

The road almost nobody starts with when they ask an AI energy question.

## 7. The Road Nobody Takes: Look at the Body


The human body is an extraordinary autonomous energy system. It acquires chemical energy from food, distributes it, converts it, stores it, repairs itself, regulates its temperature, and runs continuously for decades without scheduled maintenance.

I started with a naive question: the heart?

No. The heart is a consumer, not a producer. One or two watts of mechanical power at rest—and its electrical signals exist to control contraction, not to generate anything.

The real chain is:

food → glucose and fatty acids → mitochondria → ATP → everything else: muscles, brain, the heart itself.

A resting body runs on roughly 100 watts. The brain—the most sophisticated computation we know of—runs on about twenty.

And ATP carries the most precise lesson of the journey:

It is a currency, not a mine.

The body does not sit on a reservoir of ATP. It recycles the currency continuously—manufacturing and consuming roughly its own body weight in ATP every single day. There is no free energy. There is a tank, refilled three times a day.

And that observation suggested two directions.

## 8. Two Ideas: A Machine That Eats, and an Artificial Organ

## The first idea was straightforward: build a machine that eats.

Instead of charging a battery, let a machine consume organic fuel and extract energy from it. This is not science fiction—microbial fuel cells and enzymatic glucose cells already do versions of it.

The problem is power density. What works beautifully at the scale of a sensor does not come close to the demands of modern electronics.

Alive as a research direction. Dead, for now, as a replacement for the grid.

## The second idea was stranger: what if the intelligent component didn't sit outside the body as a separate machine at all?

What if it became an artificial organ?

An implanted device could, in principle, draw from the same biological environment as any tissue—glucose, oxygen, body heat, mechanical motion. Fed the way a kidney is fed. Not a robot you carry. A part of you.

There is real research here—implantable glucose fuel cells, thermal and kinetic harvesters. But the ceiling is unforgiving. A body can safely spare on the order of a watt. Useful inference needs hundreds to thousands.

A dead end for running large models. A wide-open road for pacemakers, implanted sensors, and neural interfaces.

## 9. Why Does the Brain Compute with Far Less Energy Than Today's LLMs?

One possibility is that the brain's extraordinary computational efficiency could be related to quantum or quantum-like processes at some level—a speculative hypothesis explored by some researchers, though it remains highly contested and lacks scientific consensus. A 2022 paper in Scientific Reports proposed that wave-like patterns in human behavioral data might be interpreted as evidence for quantum-like effects, while explicitly noting that alternative classical explanations exist and that no quantum brain hypothesis "has earned widespread acclaim".

If such a connection were ever established, it would raise a fascinating question: could quantum computing eventually enable powerful AI with dramatically lower energy requirements? Recent work is already exploring this direction. A 2025 perspective article in Quantum Science and Technology examined whether quantum algorithms could aid energy efficiency across the LLM lifecycle—noting that this remains speculative, with open research problems and no demonstrated solution at scale.

> It is worth being explicit: neither claim is established science. The first is a contested interpretation of behavioral data. The second is a forward-looking perspective on an unproven technology. Both sit firmly in the territory of open questions, not answers.

> I should also be clear that I am not a specialist in quantum computing, quantum physics, neuroscience, or any field directly related to these questions. I am exploring this idea as a speculative hypothesis, not presenting myself as an expert or claiming that it is scientifically established.
