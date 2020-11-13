#' Random Letter Generator
#' @param n number of desired random letters
#' @param letter_probs a vector of probabilities for each of the 26 letters (optional)
#' @param wreplacement if you want multiple letters, logical TRUE/FALSE for sampling with replacement
#' @return a random letter based on probabilities
#' @export
#' @examples
#' randomLetter(1) #selecct 1 random letter
#' randomLetter(2) #select 2 random letters

randomLetter = function(n, letter_probs = rep(1/26,26), wreplacement = TRUE){
  iter = sample(26, n, replace = wreplacement, prob=letter_probs)
  letter_selection = letters[iter]
  return(letter_selection)
}




