![Title PNG "Skill Factory"](./assets/skillfactory_logo.png)

# The project #4. Bank credit scoring.

The team: [Anna Kostyakova](https://github.com/anna-kostyakova), [Eldar Kalachev](https://github.com/ekalachev)

The team name on kaggle.com: **Team One**

[The noutebook](./bank_credit_scoring.ipynb)

## The task description

Welcome to the machine learning hackathon!

Imagine that you are working as an intern at a branch of a regional bank. You also do database queries and build reports. You caught yourself thinking that you imagined the work of a Data Scientist in a completely different way ...

And today, when you were already on the verge of despair, your boss came to you with the long-awaited news. Let's build a model!

“Great,” you think, “finally I can do real work!”

Your task will be to build a scoring model for the bank's secondary clients, which would predict the likelihood of a client's default. To do this, you will need to determine the significant parameters of the borrower.

### Competition conditions:
- This competition is unlimited and available for all streams.
- The deadline for the competition is set individually in each stream.
- The test sample is presented in the entire Leaderboard.
- Therefore, the best and winning solutions will be checked for their "adequacy" (so that there is no fit for the test sample).
- It is allowed to use any ML algorithms and libraries (except DL).
- We make a real ML product, which can then work normally on new data.

### Additionally
Please note that for this competition we are compiling a so-called baseline step by step on the platform, which can help you form your own winning decision.

### Quality metric
Results are estimated by [the area under the ROC AUC curve](https://en.wikipedia.org/wiki/Receiver_operating_characteristic)

### View file
For each client_id in the test suite, you must predict the probability for the default variable. The file must contain a header and have the following format:

<table>
  <tr>
    <th>client_id</th>
    <th>default</th>
  </tr>
  <tr>
    <td>66799</td>
    <td>0.44100</td>
  </tr>
   <tr>
    <td>25379</td>
    <td>0.13809174</td>
  </tr>
</table>

where `client_id` is the borrower's identifier, default is the probability of default on the loan.
