Check Your Understanding:

1) "Within a Github action that runs whenever code is pushed". Once you are sure the tests are working correctly and are comprehensive, using a github action is practical since it automatically tests pushed code, and a pull request can be modified such that unless the code passes the tests, it isn't accepted.
2) No, because E2E tests include testing of overall flow while a user is interacting with the website or app, not necessarily the correctness of an output.
3) Navigation mode analyzes the page upon load and gives information about initial performance. Snapshot mode analyzes the page in its current state. The difference is that Snapshot checks whther user interaction has caused any issues to accessibility, while navigation only checks the intial state.
4) According to the report, we can properly size images to improve load time. We can serve images in next-gen formats such as WebP and AVIF as they have better compression than PNG or JPEG, which means faster downloads and less data consumption. We can add a `<meta name="viewport">` tag that prevents 300ms delay to user input.




