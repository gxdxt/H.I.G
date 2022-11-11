People use Apple’s accessibility features to personalize how they interact with their devices in ways that work for them.
- 사람들은 애플의 접근성 기능들을 원하는 방식대로 그들의 기기와 상호작용을 어떻게 할 것인지 개인화 하기 위해 사용한다.

![](https://developer.apple.com/design/human-interface-guidelines/images/intro/foundations/foundations-accessibility-intro_2x.png)

An accessible app or game supports accessibility personalizations by design and gives everyone a great user experience, regardless of their capabilities or how they use their devices.
- 그들의 능력들 혹은 어떻게 기기들을 사용하는 지와 관계없이, 접근 가능한 앱과 게임은 ~~디자인을 통한 접근성 개인화~~를 제공하고 모두에게 훌륭한 경험을 제공합니다.

Approximately one in seven people have a disability that affects the way they interact with the world and their devices. 
- 대략적으로 7명 중 1명은 기기를 사용하는 데에 어려움을 겪습니다.
People can experience disabilities at any age, for any duration, and at varying levels of severity. 
- 사람들은 어느 나이, 어느 기간, 그리고 다양한 고통의 단계에서 불능을 경험할 수 있습니다.
For example, situational disabilities — such as a wrist injury from a fall or voice loss from overuse — can affect the way almost everyone interacts with their devices at various times.
- 예를 들어, 일시적 장애들 - 추락으로 인한 손목 골절 혹은 목을 쉰 경우 - 그들이 기기들을 사용하는 방법에 대해 영향을 끼칠 수 있습니다.

## Best practices

**Design with accessibility in mind.** 
- 접근성에 대한 디자인을 항상 생각해야 합니다.

Accessibility is not just about making information available to people with disabilities — it’s about making information available to everyone, regardless of their capabilities or situation. 
- 접근성은 불편한 사람들에게 가용한 정보를 단순히 만들어주는 것이 아닙니다. 그들의 상황과 능력과 관계 없이 모두에게 가용한 정보를 만들어주는 것입니다.

Designing your app with accessibility in mind means prioritizing _simplicity_ and _perceivability_ and examining every design decision to ensure that it doesn’t exclude people who have different abilities or interact with their devices in different ways.
- 접근성을 염두하고 앱을 디자인하는 것은 *간단*과 *지각 가능성* 그리고 모든 사람들이 각자 다른 방식으로 기기를 다루

**Simplicity** — Enabling familiar, consistent interactions that make complex tasks simple and straightforward to perform.
- 간단함 - 복잡한 업무를 간단하고 직관적으로 수행할 수 있도록 친근하고, 일관적인 상호작용을 가능하게 해야 합니다.

**Perceivability** — Making sure that all content can be perceived whether people are using sight, hearing, or touch.
- 지각 가능성 - 모든 콘텐츠들이 보거나, 듣거나, 만지는 것을 통해 지각할 수 있도록 해야합니다.

**Support personalization.** You already design your experience to adapt to environmental variations — such as device orientation, screen size, resolution, color gamut, and split view — because you want people to enjoy it in any context and on all supported devices. 
- 개인화를 지원. 당신은 이미 환경적 변화에 적응하는 경험을 디자인합니다. 예를 들어, 기기의 방향, 화면 크기, 화소, 색상 영역, 그리고 화면 분할같은 것들! 왜냐하면 당신은 사람들이 어떤 맥락과 모든 기기들을 즐기길 바라기 때문이다.

With minimal additional effort, you can design your app to support the accessibility features people use to personalize the ways they interact with their devices.
- 가장 적은 추가적인 노력으로, 당신은 사람들이 기기들을 다루는 방법으로 개인화하는 데에 사용하는 접근성 특징들을 도와주는 앱을 디자인할 수 있습니다.

When you use standard components to implement your interface, text and controls automatically adapt to several accessibility settings, such as Bold Text, Larger Text, Invert Colors, and Increase Contrast.
- 당신이 인터페이스를 구현하면서 기본적인 컴포넌트를 사용할 때, 텍스트와 컨트롤들이 자동적으로 볼드체, 큰 글씨, 색 반전, 그리고 대비 증가와 같은 여러 접근성 설정들에 적응할 것입니다.

**Audit and test your app or game for accessibility.** 
- 접근성을 위한 앱 혹은 게임 심사와 테스트

An audit examines every element in your experience and gives you a comprehensive list of issues to fix. 
- 심사는 당신의 경험 속 모든 요소를 검사하고 이해할만한 고쳐야할 요소들의 목록을 제공합니다.

Testing helps you ensure that everyone can complete the most important tasks in your app, no matter how they interact with their devices.
- 테스트는 당신이 사용자들이 어떤 방식으로 기기를 사용하더라도 당신의 앱에 가장 중요한 업무를 완료할 수 있다는 것을 확신하는 것을 도와줍니다.

When you test important user flows with accessibility features turned on, you gain an appreciation for the challenges of interacting with a device in different ways. 
- 당신이 중요한 사용자의 흐름을 접근성 특징들과 함께 테스트할 때, 당신은 다른 방법들로 기기를 사용하는 도전들에 감사할 것입니다.

You also discover places where your app might fail to deliver a great user experience.
- 당신은 또한 앱이 좋은 UX를 제공하는 것에 실패하는 환경들을 찾을 수도 있을 것입니다.

For example, a common user flow in a social media app might be “post a response to a comment.” The tasks that make up this flow could include:
- 예를 들어, 소셜 미디어 앱의 어떤 공통적인 사용자 흐름은 '댓글에 답변하기'이다. 다음과 같은 업무들이 이 흐름을 구성합니다:

-   Read posted comments
	- 게시된 댓글들을 읽습니다.
-   Choose a comment for a response
	- 답변을 위한 댓글을 선택합니다.
-   Open the response view
	- 답변 뷰를 엽니다.
-   Edit the response
	- 답변을 작성합니다.
-   Post the response
	- 답변을 게시합니다.

For each critical user flow in your app or game, turn on an accessibility feature, such as VoiceOver, Reduce Motion, or Large Text Size, and make sure that you can complete every task in the flow without difficulty. 
- 앱 혹은 게임에서의 각각의 주요한 사용자의 흐름은 Voice Over, Reduce Motion, Large Text Size 와 같은 접근 특징을 실행하고 어려움 없이 그 흐름 안에서 모든 업무를 완수할 수 있게 보장해 줍니다.

After you fix the problems you uncover, turn on a different accessibility feature and run through the user flow again. To help you audit, test, and fix your app or game, consider using Xcode’s Accessibility Inspector.
- 당신이 발견한 문제들을 고친 이후에, 또 다른 접근성 기능을 실행하고 그 사용자 흐름을 다시 한 번 실행하세요. 당신의 앱을 심사하고 테스트하고 고치도록 하는 것에 Xcode Accessibility Inspector를 이용하는 것을 고려해 보세요.

