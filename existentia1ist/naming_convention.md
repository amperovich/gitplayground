Programming Naming Conventions – Camel, Snake, Kebab, and Pascal Case Explained

If you've been programming for a while, you may have heard the words "camel case" or "pascal case". And maybe you're wondering what those terms mean. Well, let me explain.

What are Naming Conventions in Programming?

Apart from the hard and fast rules that we get with every programming language, there are also conventions. These are sets of standards that are generally accepted by the majority of developers out there.

Among all sorts of conventions, naming conventions are some of the most common. Because as programmers, we name a lot of things. Such as variables, functions, classes, methods, interfaces and so on.

Throughout the years, developers have used different case types to name different entities in their code. And four of them have proved to be the most popular ones. They are:

Camel Case

Snake Case

Kebab Case

Pascal Case

Let's have a look at some examples so you can see how these work, shall we?

What is Camel Case?

In camel case, you start a name with a small letter. If the name has multiple words, the later words will start with a capital letter:

Here are some examples of camel case: firstName and lastName.

What is Snake Case?

Like in camel case, you start the name with a small letter in snake case. If the name has multiple words, the later words will start with small letters and you use a underscore (_) to separate the words.

Here are some examples of snake case: first_name and last_name.

What is Kebab Case?

Kebab case is similar to snake case, but you use a hyphen (-) instead of an underscore (_) to separate the words.

Here are some examples of kebab case: first-name and last-name.

What is Pascal Case?

Unlike the previous examples, names in pascal case start with a capital letter. In case of the names with multiple words, all words will start with capital letters.

Here are some examples of pascal case: FirstName and LastName.

When to Use Each Naming Convention

Now, based on the language you're working on and what you're naming, the preferred case type can change.

For example, according to the PEP 8 – Style Guide for Python Code, variable and function names should use snake case:

user_name = 'Farhan'

def reverse_name(name):
	return name[::-1]
Let's take a look at JavaScript now. According to the Airbnb JavaScript Style Guide, variable and function names should use camel case:

const userName = "Farhan";

function reverseName(name) {
 	return name.split("").reverse().join("");
}
Although Python and JavaScript require you to follow different conventions when you're naming variables and functions, both languages require you to use pascal case when naming a class.

Style guides are available for more or less all popular programming languages. Here are some of the most commonly used:

Python - PEP 8 – Style Guide for Python Code
JavaScript - Airbnb JavaScript Style Guide
Java - Java style guide
C# - C# Coding Convention
Go - Uber Go Style Guide
C++ - C++ Core Guidelines
PHP - PSR-12: Extended Coding Style
These are some of the guides I've referred to in the past. There are other guides as well. Feel free to do your own research and pick the one you like. Just make sure the guide you're following is actually well regarded by the developer community.

Conclusion
These are the most popular naming conventions that you should be aware of. If you'd like to learn more about the different naming conventions, you can read through the style guide for the language you're using.

Knowing the conventions of the language you're learning is important. While not following conventions will not break your code, it'll make it less consistent and harder to work with.

Following these simple conventions, on the other hand, will make your code a lot more readable and easier to work with. So do yourself and others a favor and follow the conventions.
