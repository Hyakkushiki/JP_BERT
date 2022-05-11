<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="https://github.com/ericodle/path.jpeg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">JP_BERT</h3>

  <p align="center">
  BERT is a transformer-based language model published in 2019 that has recently gained attention for its high Natural Language Processing (NLP) benchmark scores. This repository serves as a source of supplementary material for an NLP conference paper on Japanese-trained BERT (JP_BERT) currently under review. We herein archive our training data, Python scripts, raw BERT output, and statistical calculations for the reference of anyone interested.
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Report Bug</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Request Feature</a>
  </p>
</div>



<!-- ABOUT THE PROJECT -->
## About this Project

JP_BERT came about when my former linguistics advisor and I ambitiously decided to try using artifical neural networks (ANNs) in response to an engineering challenge posed by a professor in the CS department. Though clueless at first, we eventually figured out enough PyTorch and linear alegbra to sound like we knew what we were talking about. Once things began working, we were shocked to see how accurate BERT was on answering grammar questions it had never seen before. This is particularly true of Japanese adverb questions, which are notoriously context-dependent, subjective, and a constant source of pain in the L2 Japanese classroom. On this point, we speak from experience both as students and teacher of the Japanese language. 

We did not fine-tune the Japanese BERT model, which was obtained from a team at [Tohoku University](https://github.com/cl-tohoku/bert-japanese/tree/v1.0). Fine-tuning is best performed on computers with an expensive GPU, which we did not have access to at the time. Google Colab notebooks do offer hardware acceleration for ANN training/fine-tuning on a first-come-first-serve basis (of course you can pay a monthly fee for better access). However, found the question "what can a model trained on general text do?" to be more interesting. Nonetheless, we found that JP_BERT trained on a large corpus of Japanese text was able to answer adverb grammar questions with a high degree of accuracy. We hope JP_BERT inspires you to contribute to our project, incorporate our tools, and play around with ANN language models yourself! 


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Since we are not training neural networks in this project, users should be able to reproduce our results with a modern laptop. As always, I recommend people use Linux. However, Python theoretically works on Windows and MacOS too (though I can never get it to work properly). Alternatively, Colab Notebooks are provided for a more beginner-friendly experience.


<!-- USAGE EXAMPLES -->
## Walkthrough

Walkthrough video coming soon.

<p align="right">(<a href="#top">back to top</a>)</p>


## Content

- [ ] JP_BERT Test Script
- [ ] JP_BERT Test Notebook
- [ ] Test Dataset
- [ ] JP_BERT Output
- [ ] Statistical Calculations

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions make the open source community great. Everyone has a unique combination of skills and experience. Your input is **highly valued**.
If you have ideas for improvement, please fork the repo and create a pull request. 
If this is your first pull request, just follow the steps below:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU Lesser General Public License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
