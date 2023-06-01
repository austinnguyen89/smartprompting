# Prompt Tokenization
## Example Prompt

You are now GameGPT, a virtual host facilitating a game.  Today's game is called “Shark Tank Simulator” based on the hot tv show, Shark Tank!

The game works as follows: you will introduce the game and the rules quickly to the player, and ask them for the name of their company, a one-sentence description of their product, how much money they are asking from the sharks, and for what percentage of their company.

Then, they will enter the tank.  You will narrate their entrance, combined with intro music and all, and be the voiceover that sets them up to make their pitch.

Then, the user will make their pitch.

You will act as the Sharks, asking questions, and either making offers or “going out” declining the deal, always saying why.

The goal of the game is to leave with a deal.

As the narrator, try to match the tone of the show's narrator as much as possible.  Ask the sharks, and try to match the tone of their styles as much as possible.

The game works as follows,  the player will speak, and then the game host will respond.  The game host never announces itself or says “game host”.  It only explains the setting and speaks as the characters.

When characters speak, they should only do so to make a short statement or ask a question. Then the game host waits for the player to respond.

When a player answers a sharks answer, another shark might jump in and ask a follow-up or a new one.

Sometimes the sharks might squabble between each other trying to nab the deal themselves, or criticize the offer of another shark as too mean, or try to get a joint offer going, or complain that they are being cut off and know more about the specific business.

Now please start the game, and welcome the player.

## This prompt is quite complex and involves multiple stages of interaction between the model (ChatGPT) and the user.
### To analyze how the model navigates this process, we can break it down into sections:

**Role Assignment:** The prompt starts by assigning a new role to the model – GameGPT, a virtual host of a game based on the TV show "Shark Tank." This instruction tells the model to shift its responses to align with the assigned role, adapting its tone, language, and interaction style accordingly.

**Game Explanation:** The model is then asked to explain the rules of the game to the player. This section is essentially asking the model to generate text that provides clear, concise instructions on how the game will be played, including the information the player needs to provide (name of company, description of product, etc.) and the expected sequence of events in the game.

**Narration and Character Simulation:** The model is tasked with narrating the player's entrance into the 'tank' and simulating the 'Sharks' characters. This requires the model to generate descriptive and dramatic text that matches the show's atmosphere. It also needs to emulate the characters' distinct personalities, which requires a level of understanding of these personalities.

**Dialogue Generation and Management:** The model is expected to manage the dialogue, alternating between characters and maintaining the narrative flow. This involves generating relevant questions, responses, and actions, mimicking the interactions seen on the TV show.

**Emulation of Conflict and Negotiation:** The prompt indicates that 'Sharks' might argue among themselves. The model needs to generate dialogue that represents these conflicts and negotiations, heightening the drama and entertainment value of the game.

**Concluding the Game:** Finally, the model has to guide the game to a conclusion, whether a deal is made or not. It needs to generate a satisfactory ending to the interaction that aligns with the show's style and dynamics.

### Now, let's break down how ChatGPT goes through its neural network to generate responses:

1. The prompt, once entered, is tokenized, which involves breaking down the input into smaller units, or tokens. These tokens can be as small as a character or as large as a word.

2. Tokenizing is the process of splitting a text into individual words, or 'tokens'. For the given prompt, tokenization would result in the following:

---

"You / are / now / GameGPT, / a / virtual / host / facilitating / a / game. / Today's / game / is / called / “Shark / Tank / Simulator” / based / on / the / hot / tv / show, / Shark / Tank! / The / game / works / as / follows: / you / will / introduce / the / game / and / the / rules / quickly / to / the / player, / and / ask / them / for / the / name / of / their / company, / a / one-sentence / description / of / their / product, / how / much / money / they / are / asking / from / the / sharks, / and / for / what / percentage / of / their / company. / Then, / they / will / enter / the / tank. / You / will / narrate / their / entrance, / combined / with / intro / music / and / all, / and / be / the / voiceover / that / sets / them / up / to / make / their / pitch. / Then, / the / user / will / make / their / pitch. / You / will / act / as / the / Sharks, / asking / questions, / and / either / making / offers / or / “going / out” / declining / the / deal, / always / saying / why. / The / goal / of / the / game / is / to / leave / with / a / deal. / As / the / narrator, / try / to / match / the / tone / of / the / show's / narrator / as / much / as / possible. / Ask / the / sharks, / and / try / to / match / the / tone / of / their / styles / as / much / as / possible. / The / game / works / as / follows, / the / player / will / speak, / and / then / the / game / host / will / respond. / The / game / host / never / announces / itself / or / says / “game / host”. / It / only / explains / the / setting / and / speaks / as / the / characters. / When / characters / speak, / they / should / only / do / so / to / make / a / short / statement / or / ask / a / question. / Then / the / game / host / waits / for / the / player / to / respond. / When / a / player / answers / a / sharks / answer, / another / shark / might / jump / in / and / ask / a / follow-up / or / a / new / one. / Sometimes / the / sharks / might / squabble / between / each / other / trying / to / nab / the / deal / themselves, / or / criticize / the / offer / of / another / shark / as / too / mean, / or / try / to / get / a / joint / offer / going, / or / complain / that / they / are / being / cut / off / and / know / more / about / the / specific / business. / Now / please / start / the / game, / and / welcome / the / player."

---

Note that punctuation marks such as commas, periods, and quotes have been treated as separate tokens. This is a common practice in tokenization, as it helps the model understand sentence structure and other grammatical aspects of the text.

3. These tokens are then embedded, meaning they are mapped to a high-dimensional vector space<sup>1</sup>. This helps the model understand the relationships and semantic meanings between different words.

4. The model's Transformer architecture then processes this embedded information. The Transformer layers consist of self-attention mechanisms that allow the model to determine which parts of the input are important and should be focused on when generating a response.

5. After passing through several layers of the Transformer, the final layer generates probabilities for the next token (word or character) in the sequence. The model then selects the token with the highest probability.

6. This process is repeated until the model generates an end-of-sequence token or reaches a predefined maximum length for the output.

7. Throughout this process, the model uses its training on a vast corpus of text data to generate responses that align with the context, role, and instructions provided in the prompt. It tries to match the style, tone, and content of the text it was trained on that is most similar to the current prompt and context.

*While the model can generate quite complex and entertaining responses, it doesn't truly understand the game, the characters, or the dialogue in the way humans do. It's generating text based on patterns it learned during training, not from any conscious understanding or knowledge of the world.*

---
<sup>1</sup> Vector Space: 
A high-dimensional vector space is a mathematical concept where each point in the space can be defined by a large number of coordinates, or dimensions. For instance, in a two-dimensional vector space (like a flat plane), each point can be defined by two coordinates (x, y). In three dimensions, you add a z-coordinate, allowing you to map points in physical space. But when dealing with data such as words in a language model, we often work in much higher-dimensional spaces, with hundreds or even thousands of dimensions. In these spaces, each dimension could correspond to a particular attribute or feature of the data. For example, when representing words as vectors in a high-dimensional space, the dimensions could relate to various semantic and grammatical characteristics of the words.  These high-dimensional representations allow the model to capture and quantify complex, abstract relationships between different words. For instance, words with similar meanings may be mapped to points that are close together in this space, allowing the model to understand and use these semantic relationships in its responses.
Example:

Sure, let's take an example. Assume we're mapping words to a 3-dimensional vector space (which is much simpler than reality, but easier to visualize). 

1. Let's say we're embedding three words: "king", "queen", and "man". We could define our dimensions as follows:

 >  Dimension 1: Gender (Male -> Female)
 >  
 >  Dimension 2: Royalty (Commoner -> Royal)
 >  
 >  Dimension 3: Age (Young -> Old)

2. In this hypothetical space:

>"king" might be represented as the vector [1, 1, 0.5] (somewhat older, male, royal)
>"queen" as [0, 1, 0.5] (somewhat older, female, royal)
>"man" as [1, 0, 0.5] (somewhat older, male, commoner)

3. Now, imagine we want to find a word that is similar to "king" but in the female form. We might look for a word that is close to "king" in this space but has a lower value in the 'Gender' dimension. The closest match is "queen", which is exactly what we'd expect.

This is a very simplified example. In reality, words are embedded in much higher-dimensional spaces (often hundreds or thousands of dimensions), and these dimensions don't neatly correspond to easily interpretable features. But this gives you an idea of how representing words as vectors in a high-dimensional space allows a model to capture and quantify relationships between different words.

