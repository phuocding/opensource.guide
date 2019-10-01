---
lang: vi
title: Best Practices for Maintainers
description: Làm cho cuộc sống của bạn dễ dàng hơn như một người bảo trì nguồn mở, từ các tài liệu quy trình đến tận dụng cộng đồng của bạn.
class: best-practices
order: 5
image: /assets/images/cards/best-practices.png
related:
  - metrics
  - leadership
---

## Một người bảo trì có nghĩa là gì?

Nếu bạn duy trì một dự án nguồn mở mà nhiều người sử dụng, bạn có thể nhận thấy bạn đang viết mã ít hơn và phản hồi các vấn đề nhiều hơn.

Trong giai đoạn đầu của một dự án, bạn đang thử nghiệm những ý tưởng mới và đưa ra quyết định dựa trên những gì bạn muốn. Khi dự án của bạn tăng mức độ phổ biến, bạn sẽ thấy mình làm việc với người dùng và cộng tác viên nhiều hơn.

Duy trì một dự án đòi hỏi nhiều hơn mã. Những nhiệm vụ này thường bất ngờ, nhưng chúng cũng quan trọng đối với một dự án đang phát triển. Chúng tôi đã tập hợp một vài cách để làm cho cuộc sống của bạn dễ dàng hơn, từ ghi lại các quy trình cho đến tận dụng cộng đồng của bạn.

## Tài liệu về các quy trình của bạn

Viết mọi thứ xuống là một trong những điều quan trọng nhất bạn có thể làm như một người bảo trì.

Tài liệu không chỉ làm rõ suy nghĩ của riêng bạn, mà nó còn giúp người khác hiểu bạn cần gì hoặc mong đợi gì, trước khi họ hỏi.

Viết ra những điều giúp bạn dễ dàng nói không khi điều gì đó không phù hợp với phạm vi của bạn. Nó cũng giúp mọi người dễ dàng tham gia và giúp đỡ hơn. Bạn không bao giờ biết ai có thể đang đọc hoặc sử dụng dự án của bạn.

Ngay cả khi bạn không sử dụng các đoạn văn đầy đủ, ghi lại các gạch đầu dòng vẫn tốt hơn là không viết gì cả.

Hãy nhớ giữ tài liệu của bạn cập nhật. Nếu bạn không thể luôn luôn làm điều này, hãy xóa tài liệu lỗi thời của bạn hoặc cho biết nó đã lỗi thời để những người đóng góp biết các bản cập nhật được chào đón.

### Viết ra tầm nhìn dự án của bạn

Bắt đầu bằng cách viết ra các mục tiêu của dự án của bạn. Thêm chúng vào README của bạn hoặc tạo một tệp riêng gọi là VISION. Nếu có những đồ tạo tác khác có thể giúp đỡ, như lộ trình dự án, hãy làm cho chúng công khai.

Có một tầm nhìn rõ ràng, được ghi lại trong tài liệu giúp bạn tập trung và giúp bạn tránh "phạm vi leo trèo" khỏi những đóng góp của người khác.

Ví dụ: @lord phát hiện ra rằng có tầm nhìn dự án giúp anh ta tìm ra yêu cầu nào dành thời gian cho nó. Là một người bảo trì mới, anh ta hối hận vì đã không tuân thủ phạm vi dự án của mình khi nhận được yêu cầu tính năng đầu tiên cho [Slate](https://github.com/lord/slate).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/lord?s=180" class="pquote-avatar" alt="avatar">
  Tôi dò dẫm nó. Tôi đã không nỗ lực để đưa ra một giải pháp hoàn chỉnh. Thay vì một giải pháp nửa vời, tôi ước rằng tôi đã nói "Tôi không có thời gian cho việc này ngay bây giờ, nhưng tôi sẽ thêm nó vào danh sách dài hạn tốt đẹp để có."
  <p markdown="1" class="pquote-credit">
— @lord, ["Mẹo cho các nhà duy trì nguồn mở mới"](https://lord.io/blog/2014/oss-tips/)
  </p>
</aside>

### Truyền đạt sự mong đợi của bạn

Các quy tắc có thể là thần kinh để viết ra. Đôi khi bạn có thể cảm thấy như bạn đang kiểm soát hành vi của người khác hoặc giết chết tất cả những niềm vui.

Văn bản và thực thi công bằng, tuy nhiên, các quy tắc tốt trao quyền cho người duy trì. Chúng ngăn bạn khỏi bị lôi kéo vào làm những việc bạn không muốn làm.

Hầu hết những người đi qua dự án của bạn không biết gì về bạn hoặc hoàn cảnh của bạn. Họ có thể cho rằng bạn được trả tiền để làm việc với nó, đặc biệt nếu đó là thứ họ thường xuyên sử dụng và phụ thuộc vào. Có thể tại một thời điểm, bạn dành rất nhiều thời gian cho dự án của mình, nhưng bây giờ bạn đang bận rộn với một công việc mới hoặc thành viên gia đình.

Tất cả điều này là hoàn toàn ổn! Chỉ cần chắc chắn rằng những người khác biết về nó.

Nếu việc duy trì dự án của bạn là bán thời gian hoặc hoàn toàn tự nguyện, hãy thành thật về thời gian bạn có. Điều này không giống như bạn nghĩ dự án cần bao nhiêu thời gian, hoặc người khác muốn bạn dành bao nhiêu thời gian.

Dưới đây là một vài quy tắc đáng để viết ra:

* Làm thế nào một đóng góp được xem xét và chấp nhận (_Họ có cần thử nghiệm không? Mẫu vấn đề?_)
* Các loại đóng góp bạn sẽ chấp nhận (_Bạn chỉ muốn giúp đỡ với một phần nhất định của mã của bạn_)
* Khi nào thì thích hợp để theo dõi (_ví dụ: "Bạn có thể mong đợi phản hồi từ người bảo trì trong vòng 7 ngày. Nếu sau đó bạn chưa nghe thấy gì, hãy thoải mái ping chủ đề."_)
* Bạn dành bao nhiêu thời gian cho dự án (_ví dụ: "Chúng tôi chỉ dành khoảng 5 giờ mỗi tuần cho dự án này"_)

[Jekyll](https://github.com/jekyll/jekyll/tree/master/docs), [CocoaPods](https://github.com/CocoaPods/CocoaPods/wiki/Communication-&-Design-Rules), và [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Maintainers-Avoiding-Burnout.md) là một số ví dụ về các dự án với các quy tắc cơ bản cho người bảo trì và người đóng góp.

### Giữ liên lạc công khai

Đừng quên ghi lại các tương tác của bạn. Bất cứ nơi nào bạn có thể, hãy giữ thông tin liên lạc về dự án của bạn công khai. Nếu ai đó cố gắng liên lạc riêng với bạn để thảo luận về yêu cầu tính năng hoặc nhu cầu hỗ trợ, hãy lịch sự hướng họ đến một kênh liên lạc công cộng, chẳng hạn như danh sách gửi thư hoặc theo dõi vấn đề.

Nếu bạn gặp những người bảo trì khác hoặc đưa ra quyết định lớn ở chế độ riêng tư, hãy ghi lại những cuộc trò chuyện này ở nơi công cộng, ngay cả khi đó chỉ là đăng các ghi chú của bạn.

Bằng cách đó, bất kỳ ai tham gia cộng đồng của bạn sẽ có quyền truy cập vào cùng thông tin như ai đó đã ở đó trong nhiều năm.

## Học cách nói không
Bạn đã viết những điều xuống. Lý tưởng nhất là mọi người sẽ đọc tài liệu của bạn, nhưng trong thực tế, bạn sẽ phải nhắc nhở người khác rằng kiến ​​thức này tồn tại.

Tuy nhiên, có tất cả mọi thứ được viết ra giúp cá nhân hóa các tình huống khi bạn cần thực thi các quy tắc của mình.

Nói không vui, nhưng _"Đóng góp của bạn không phù hợp với tiêu chí của dự án này"_ cảm thấy ít cá nhân hơn _"Tôi không thích sự đóng góp của bạn"_.

Nói không áp dụng cho nhiều tình huống bạn sẽ gặp phải với tư cách là người bảo trì: các yêu cầu tính năng không phù hợp với phạm vi, ai đó làm hỏng một cuộc thảo luận, làm những việc không cần thiết cho người khác.

### Giữ cho cuộc trò chuyện thân thiện

Một trong những nơi quan trọng nhất bạn sẽ thực hành nói không là về vấn đề của bạn và kéo hàng yêu cầu. Là người duy trì dự án, chắc chắn bạn sẽ nhận được các đề xuất mà bạn không muốn chấp nhận.

Có thể sự đóng góp thay đổi phạm vi dự án của bạn hoặc không phù hợp với tầm nhìn của bạn. Có thể ý tưởng là tốt, nhưng thực hiện là kém.

Bất kể lý do là gì, có thể xử lý khéo léo các đóng góp không đáp ứng các tiêu chuẩn của dự án của bạn.

Nếu bạn nhận được một đóng góp mà bạn không muốn chấp nhận, phản ứng đầu tiên của bạn có thể là bỏ qua nó hoặc giả vờ như bạn không thấy nó. Làm như vậy có thể làm tổn thương cảm xúc của người khác và thậm chí làm mất lòng những người đóng góp tiềm năng khác trong cộng đồng của bạn.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/krausefx?s=180" class="pquote-avatar" alt="avatar">
  Chìa khóa để xử lý hỗ trợ cho các dự án nguồn mở quy mô lớn là giữ cho các vấn đề được di chuyển. Cố gắng tránh gặp sự cố gian hàng. Nếu bạn là một nhà phát triển iOS, bạn sẽ biết việc nản lòng đến mức nào khi gửi radar. Bạn có thể nghe lại 2 năm sau và được yêu cầu thử lại với phiên bản iOS mới nhất.
  <p markdown="1" class="pquote-credit">
— @KrauseFx, ["Mở rộng quy mô cộng đồng nguồn mở"](https://krausefx.com/blog/scaling-open-source-communities)
  </p>
</aside>

Don't leave an unwanted contribution open because you feel guilty or want to be nice. Over time, your unanswered issues and PRs will make working on your project feel that much more stressful and intimidating.

It's better to immediately close the contributions you know you don't want to accept. If your project already suffers from a large backlog, @steveklabnik has suggestions for [how to triage issues efficiently](https://words.steveklabnik.com/how-to-be-an-open-source-gardener).

Secondly, ignoring contributions sends a negative signal to your community. Contributing to a project can be intimidating, especially if it's someone's first time. Even if you don't accept their contribution, acknowledge the person behind it and thank them for their interest. It's a big compliment!

If you don't want to accept a contribution:

* **Thank them** for their contribution
* **Explain why it doesn't fit** into the scope of the project, and offer clear suggestions for improvement, if you're able. Be kind, but firm.
* **Link to relevant documentation**, if you have it. If you notice repeated requests for things you don't want to accept, add them into your documentation to avoid repeating yourself.
* **Close the request**

You shouldn't need more than 1-2 sentences to respond. For example, when a user of [celery](https://github.com/celery/celery/) reported a Windows-related error, @berkerpeksag [responded with](https://github.com/celery/celery/issues/3383):

![Celery screenshot](/assets/images/best-practices/celery.png)

If the thought of saying no terrifies you, you're not alone. As @jessfraz [put it](https://blog.jessfraz.com/post/the-art-of-closing/):

> I've talked to maintainers from several different open source projects, Mesos, Kubernetes, Chromium, and they all agree one of the hardest parts of being a maintainer is saying "No" to patches you don't want.

Don't feel guilty about not wanting to accept someone's contribution. The first rule of open source, [according to](https://twitter.com/solomonstre/status/715277134978113536) @shykes: _"No is temporary, yes is forever."_ While empathizing with another person's enthusiasm is a good thing, rejecting a contribution is not the same as rejecting the person behind it.

Ultimately, if a contribution isn't good enough, you're under no obligation to accept it. Be kind and responsive when people contribute to your project, but only accept changes that you truly believe will make your project better. The more often you practice saying no, the easier it becomes. Promise.

### Hãy chủ động
To reduce the volume of unwanted contributions in the first place, explain your project's process for submitting and accepting contributions in your contributing guide.

If you're receiving too many low-quality contributions, require that contributors do a bit of work beforehand, for example:

* Fill out a issue or PR template/checklist
* Open an issue before submitting a PR

If they don't follow your rules, close the issue immediately and point to your documentation.

While this approach may feel unkind at first, being proactive is actually good for both parties. It reduces the chance that someone will put in many wasted hours of work into a pull request that you aren't going to accept. And it makes your workload easier to manage.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/mikemcquaid?s=180" class="pquote-avatar" alt="avatar">
  Ideally, explain to them and in a CONTRIBUTING.md file how they can get a better indication in the future on what would or would not be accepted before they begin the work.
  <p markdown="1" class="pquote-credit">
— @MikeMcQuaid, ["Kindly Closing Pull Requests"](https://github.com/blog/2124-kindly-closing-pull-requests)
  </p>
</aside>

Sometimes, when you say no, your potential contributor may get upset or criticize your decision. If their behavior becomes hostile, [take steps to defuse the situation](https://github.com/jonschlinkert/maintainers-guide-to-staying-positive#action-items) or even remove them from your community, if they're not willing to collaborate constructively.

### Embrace mentorship

Maybe someone in your community regularly submits contributions that don't meet your project's standards. It can be frustrating for both parties to repeatedly go through rejections.

If you see that someone is enthusiastic about your project, but needs a bit of polish, be patient. Explain clearly in each situation why their contributions don't meet the expectations of the project. Try pointing them to an easier or less ambiguous task, like an issue marked _"good first issue,"_ to get their feet wet. If you have time, consider mentoring them through their first contribution, or find someone else in your community who might be willing to mentor them.

## Leverage your community

You don't have to do everything yourself. Your project's community exists for a reason! Even if you don't yet have an active contributor community, if you have a lot of users, put them to work.

### Share the workload

If you're looking for others to pitch in, start by asking around.

One way to gain new contributors is to explicitly [label issues that are simple enough for beginners to tackle](https://help.github.com/en/articles/helping-new-contributors-find-your-project-with-labels). GitHub will then surface these issues in various places on the platform, increasing their visibility.

When you see new contributors making repeated contributions, recognize their work by offering more responsibility. Document how others can grow into leadership roles if they wish.

Encouraging others to [share ownership of the project](../building-community/#share-ownership-of-your-project) can greatly reduce your own workload, as @lmccart discovered on her project, [p5.js](https://github.com/processing/p5.js).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/lmccart?s=180" class="pquote-avatar" alt="avatar">
  I’d been saying, "Yeah, anyone can be involved, you don’t have to have a lot of coding expertise [...]." We had people sign up to come [to an event] and that’s when I was really wondering: is this true, what I’ve been saying? There are gonna be 40 people who show up, and it’s not like I can sit with each of them...But people came together, and it just sort of worked. As soon as one person got it, they could teach their neighbor.
  <p markdown="1" class="pquote-credit">
—  @lmccart, ["What Does "Open Source" Even Mean? p5.js Edition"](https://medium.com/@kenjagan/what-does-open-source-even-mean-p5-js-edition-98c02d354b39)
  </p>
</aside>

If you need to step away from your project, either on hiatus or permanently, there's no shame in asking someone else to take over for you.

If other people are enthusiastic about its direction, give them commit access or formally hand over control to someone else. If someone forked your project and is actively maintaining it elsewhere, consider linking to the fork from your original project. It's great that so many people want your project to live on!

@progrium [found that](https://progrium.com/blog/2015/12/04/leadership-guilt-and-pull-requests/) documenting the vision for his project, [Dokku](https://github.com/dokku/dokku), helped those goals live on even after he stepped away from the project:

> I wrote a wiki page describing what I wanted and why I wanted it. For some reason it came as a surprise to me that the maintainers started moving the project in that direction! Did it happen exactly how I'd do it? Not always. But it still brought the project closer to what I wrote down.

### Let others build the solutions they need

If a potential contributor has a different opinion on what your project should do, you may want to gently encourage them to work on their own fork.

Forking a project doesn't have to be a bad thing. Being able to copy and modify projects is one of the best things about open source. Encouraging your community members to work on their own fork can provide the creative outlet they need, without conflicting with your project's vision.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/geerlingguy?s=180" class="pquote-avatar" alt="avatar">
  I cater to the 80% use case. If you are one of the unicorns, please fork my work. I won't get offended! My public projects are almost always meant to solve the most common problems; I try to make it easy to go deeper by either forking my work or extending it.
  <p markdown="1" class="pquote-credit">
— @geerlingguy, ["Why I Close PRs"](https://www.jeffgeerling.com/blog/2016/why-i-close-prs-oss-project-maintainer-notes)
  </p>
</aside>

The same applies to a user who really wants a solution that you simply don't have the bandwidth to build. Offering APIs and customization hooks can help others meet their own needs, without having to modify the source directly. @orta [found that](https://artsy.github.io/blog/2016/07/03/handling-big-projects/) encouraging plugins for CocoaPods led to "some of the most interesting ideas":

> It's almost inevitable that once a project becomes big, maintainers have to become a lot more conservative about how they introduce new code. You become good at saying "no", but a lot of people have legitimate needs. So, instead you end up converting your tool into a platform.

## Bring in the robots

Just as there are tasks that other people can help you with, there are also tasks that no human should ever have to do. Robots are your friend. Use them to make your life as a maintainer easier.

### Require tests and other checks to improve the quality of your code

One of the most important ways you can automate your project is by adding tests.

Tests help contributors feel confident that they won't break anything. They also make it easier for you to review and accept contributions quickly. The more responsive you are, the more engaged your community can be.

Set up automatic tests that will run on all incoming contributions, and ensure that your tests can easily be run locally by contributors. Require that all code contributions pass your tests before they can be submitted. You'll help set a minimum standard of quality for all submissions. [Required status checks](https://help.github.com/articles/about-required-status-checks/) on GitHub can help ensure no change gets merged without your tests passing.

If you add tests, make sure to explain how they work in your CONTRIBUTING file.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/edunham?s=180" class="pquote-avatar" alt="avatar">
  I believe that tests are necessary for all code that people work on. If the code was fully and perfectly correct, it wouldn't need changes – we only write code when something is wrong, whether that's "It crashes" or "It lacks such-and-such a feature". And regardless of the changes you're making, tests are essential for catching any regressions you might accidentally introduce.
  <p markdown="1" class="pquote-credit">
— @edunham, ["Rust's Community Automation"](https://edunham.net/2016/09/27/rust_s_community_automation.html)
  </p>
</aside>

### Use tools to automate basic maintenance tasks

The good news about maintaining a popular project is that other maintainers have probably faced similar issues and built a solution for it.

There are a [variety of tools available](https://github.com/showcases/tools-for-open-source) to help automate some aspects of maintenance work. A few examples:

* [semantic-release](https://github.com/semantic-release/semantic-release) automates your releases
* [mention-bot](https://github.com/facebook/mention-bot) mentions potential reviewers for pull requests
* [Danger](https://github.com/danger/danger) helps automate code review
* [no-response](https://github.com/probot/no-response) closes issues where the author hasn't responded to a request for more information
* [dependabot-preview](https://github.com/marketplace/dependabot-preview) checks your dependency files every day for outdated requirements and opens individual pull requests for any it finds

For bug reports and other common contributions, GitHub has [Issue Templates and Pull Request Templates](https://github.com/blog/2111-issue-and-pull-request-templates), which you can create to streamline the communication you receive. @TalAter made a [Choose Your Own Adventure guide](https://www.talater.com/open-source-templates/#/) to help you write your issue and PR templates.

To manage your email notifications, you can set up [email filters](https://github.com/blog/2203-email-updates-about-your-own-activity) to organize by priority.

If you want to get a little more advanced, style guides and linters can standardize project contributions and make them easier to review and accept.

However, if your standards are too complicated, they can increase the barriers to contribution. Make sure you're only adding enough rules to make everyone's lives easier.

If you're not sure which tools to use, look at what other popular projects do, especially those in your ecosystem. For example, what does the contribution process look like for other Node modules? Using similar tools and approaches will also make your process more familiar to your target contributors.

## It's okay to hit pause

Open source work once brought you joy. Maybe now it's starting to make you feel avoidant or guilty.

Perhaps you're feeling overwhelmed or a growing sense of dread when you think about your projects. And meanwhile, the issues and pull requests pile up.

Burnout is a real and pervasive issue in open source work, especially among maintainers. As a maintainer, your happiness is a non-negotiable requirement for the survival of any open source project.

Although it should go without saying, take a break! You shouldn't have to wait until you feel burned out to take a vacation. @brettcannon, a Python core developer, decided to take [a month-long vacation](https://snarky.ca/why-i-took-october-off-from-oss-volunteering/) after 14 years of volunteer OSS work.

Just like any other type of work, taking regular breaks will keep you refreshed, happy, and excited about your work.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/danielbachhuber?s=180" class="pquote-avatar" alt="avatar">
  In maintaining WP-CLI, I've discovered I need to make myself happy first, and set clear boundaries on my involvement. The best balance I've found is 2-5 hours per week, as a part of my normal work schedule. This keeps my involvement a passion, and from feeling too much like work. Because I prioritize the issues I'm working on, I can make regular progress on what I think is most important.
  <p markdown="1" class="pquote-credit">
— @danielbachhuber, ["My condolences, you're now the maintainer of a popular open source project"](https://runcommand.io/2016/06/26/my-condolences-youre-now-the-maintainer-of-a-popular-open-source-project/)
  </p>
</aside>

Sometimes, it can be hard to take a break from open source work when it feels like everybody needs you. People may even try to make you feel guilty for stepping away.

Do your best to find support for your users and community while you're away from a project. If you can't find the support you need, take a break anyway. Be sure to communicate when you're not available, so people aren't confused by your lack of responsiveness.

Taking breaks applies to more than just vacations, too. If you don't want to do open source work on weekends, or during work hours, communicate those expectations to others, so they know not to bother you.

## Take care of yourself first!

Maintaining a popular project requires different skills than the earlier stages of growth, but it's no less rewarding. As a maintainer, you'll practice leadership and personal skills on a level that few people get to experience. While it's not always easy to manage, setting clear boundaries and only taking on what you're comfortable with will help you stay happy, refreshed, and productive.
