# 5-letter-lock-combinations
An alphabetized list of likely combinations for various 5-letter combination locks

All credit goes to Reddit user navyjeff: https://www.reddit.com/r/lockpicking/comments/4a6rnj/5_letter_combo_lock_seeking_word_list_or_link_for/

I'm just reproducing the work here and storing the results in a more permenant place for future reference.
**NOTE** This technique is incomplete. It only includes 5-digit combinations, but most 5-letter combo locks include a "space" and thus allow 4-digit combos

The technique:

Download word list: http://www-cs-faculty.stanford.edu/~uno/sgb-words.txt

Regular expression magic: cat sgb-words.txt | grep "[jlmnprstbd][oayrtleiuh][ldnorstace][lhnyrstedk][adeinrsty]" >> words.txt

Alphabetize: cat words.txt | sort -d >> words-sorted.txt

