- 👋 Hi, I’m Parth
- 👀 I’m interested in Web Development and Competitive Programming
- 🌱 I’m currently pursuing Bachelor's Of Technology(CSE).
- 💞️ I’m looking to explore new technologies.


<!---
parth375/parth375 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
return DefaultTextStyle(
  style: const TextStyle(
    fontSize: 20.0,
  ),
  child: AnimatedTextKit(
    animatedTexts: [
      WavyAnimatedText('Hello World'),
      WavyAnimatedText('Look at the waves'),
    ],
    isRepeatingAnimation: true,
    onTap: () {
      print("Tap Event");
    },
  ),
);
