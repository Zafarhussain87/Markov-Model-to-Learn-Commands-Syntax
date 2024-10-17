# Learning the Structure of Commands by Detecting Random Tokens Using Markov Model

Learning the syntax and structure of command-line commands is of utmost importance in the field of cyber security to identify valid
and malicious sets of commands. It is hard to learn the syntax and structure of every command because of various reasons, such as
the continuous evolution of commands, precise syntax requirement, huge volume of available commands, and no room for errors,
etc. In this research work, we studied two approaches to learning the structure of the commands by detecting the random tokens in
them, such as temp files, temp directories, numerical values, etc. In the first approach, we write hard-coded regular expressions to
identify random tokens in a command whereas in the second approach we trained a second-order Markov model which detects the
random tokens based on their probabilities. To validate the efficiency of these approaches, we clustered the commands using their
word embeddings and sentence embeddings. For clustering, we explored KMeans, and DBScan with word embeddings and sentence
clustering based on sentence embeddings. We evaluated the performance of clustering algorithms against three metrics, the Silhouette
Coefficient, the Calinski-Harabasz Index, and the Davies-Bouldin Index. The results show that regular expression and the Markov
model achieve the same scores for KMeans and DBScan based on word embeddings against three metrics, whereas when clustered
using sentence embeddings, the Markov model performs better than regular expression. These results validate our idea of using the
Markov model instead of regular expressions, to get similar scores or even better performance with less resource utilization, such as
human effort, time to write regular expressions, and maintaining & storage of those regular expressions.

# Cite as:
Hussain, Z., Nurminen, J. K. & Ranta-aho, P. “Learning the Structure of Commands by Detecting Random Tokens Using Markov Model” 8th International Conference on Machine Learning Technologies, 2023, ACM.
