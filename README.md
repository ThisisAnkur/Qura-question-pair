# Qura-question-pair
This is a Qura-questionn-pair  similarity based ml model.

Quora is a platform for Q&A, just like StackOverflow. But quora is more of a general-purpose Q&A platform that means there is not much code like in StackOverflow

One of the many problems that quora face is the duplication of questions. Duplication of question ruins the experience for both the questioner and the answerer. Since the questioner is asking a duplicate question, we can just show him/her the answers to the previous question. And the answer doesn’t have to repeat his/her answer for essentially the same questions.

For example, we have a question like “How can I be a good geologist?” and there are some answers to that question. Later someone else asks another question like “What should I do to be a great geologist?”.

We can see that both the questions are asking the same thing. Even though the wordings for the question are different, the intention of both questions is the same.

So the answers will be the same for both questions. That means we can just show the answers to the first question. That way the person who is asking the question will get the answers immediately and people who have answered already the first question don’t have to repeat themselves.

This problem is available on Kaggle as a competition.

So given two questions, our main objective is to find whether they are similar. So let’s do some magic with ML.
