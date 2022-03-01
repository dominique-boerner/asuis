# Simple UI System

A test project in which the goal is to define a structure for custom design systems.

## Why thinking about the design-system architecture? 🤔

As a software developer, you spend most of your time looking for things in the code. While IDEs offer a great advantage to search or jump globally for variables, you also create a certain dependency on your tool.

In times of Bootstrap, Google Material and other great libraries to quickly and easily create your own website, something always stands out: What happens when you experiment with them and realize that the corresponding library is not enough? Or doesn't meet your expectations at all?

In order to allow the exchange or even bilateral use of these libraries, a certain base of design definitions should be able to be expanded - regardless of the design system.

**Note: The repository is an experiment and serves the development and elaboration of a more-or-less standard for projects. Ideas and comments are welcome and appreciated.**

## File Structure 📁

```text
│   component.scss          # import every component in this file
│   fonts.scss              # definition of font families
│   normalize.scss          # normalize your theme
│   palette.scss            # create your color palette
│   shadow.scss             # define your shadows
│   spacing.scss            # define your spacings
│   theme.scss              # import every root scss file
│   typography.scss         # define your font sizes here
│   utility.scss            # import the utility classes here
│   _functions.scss         # functions for accessing your variables / definitions
│
├───components              # put your global component scss here
│       card.scss           # example card component
│
└───utility                 # put your utility classes here
        fonts.util.scss
        palette.util.scss
        spacing.util.scss
        text.util.scss

```

## Live Preview

The project is deployed at [Netlify](https://quirky-heyrovsky-811bb1.netlify.app).
