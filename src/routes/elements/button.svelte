<script>
  import {
    Block,
    Buttons,
    Column,
    Columns,
    Container,
    Content,
    Hero,
    HeroBody,
    HeroHead,
    Section,
    Title,
  } from 'bulma-svelte';
  import Button from 'bulma-svelte/src/components/button/button.svelte';
</script>

<Container isFluid>
  <Block>
    <Hero size="is-small">
      <HeroBody>
        <Title size="is-1">Button</Title>
        <Title type="subtitle" size="is-4" color="has-text-grey"
          >The classic <strong>button</strong>, in different colors, sizes, and states</Title>
      </HeroBody>
      <hr />
    </Hero>
  </Block>
  <Section>
    <Title size="is-5" type="subtitle" color="has-text-dark"
      >The <strong>button</strong> is an essential element of any design. It's meant to look and behave as an interactive
      element of your page.</Title>
  </Section>
  <Section>
    <Block>
      <Title type="subtitle" size="is-4">Color</Title>
      <Button>Standart</Button>
      <Button color="is-white">White</Button>
      <Button color="is-light">Light</Button>
      <Button color="is-dark">Dark</Button>
      <Button color="is-black">Black</Button>
      <Button color="is-primary">Primary</Button>
      <Button color="is-success">Success</Button>
      <Button color="is-danger">Danger</Button>
      <Button color="is-warning">Warning</Button>
      <Button color="is-info">Info</Button>
      <Button color="is-link">Link</Button>
      <Button color="is-ghost">Ghost</Button>
      <Button color="is-text">Text</Button>
    </Block>
    <Block>
      <Button isLight color="is-primary">Light-Primary</Button>
      <Button isLight color="is-success">Light-Success</Button>
      <Button isLight color="is-danger">Light-Danger</Button>
      <Button isLight color="is-warning">Light-Warning</Button>
      <Button isLight color="is-info">Light-Info</Button>
      <Button isLight color="is-link">Light-Link</Button>
    </Block>
  </Section>

  <Section>
    <Title type="subtitle" size="is-4">Size</Title>
    <Buttons>
      <Button size="is-small">Small</Button>
      <Button size="is-normal">Normal</Button>
      <Button size="is-medium">Medium</Button>
      <Button size="is-large">Large</Button>
    </Buttons>
  </Section>

  <Section>
    <Title type="subtitle" size="is-4">Displays</Title>
    <Buttons>
      <Button isFullWidth size="is-small">Full width Small</Button>
      <Button isFullWidth size="is-normal">Full width Normal</Button>
      <Button isFullWidth size="is-medium">Full width Medium</Button>
      <Button isFullWidth size="is-large">Full width Large</Button>
    </Buttons>
  </Section>

  <Section>
    <Title type="subtitle" size="is-4">Styles</Title>
    <Buttons>
      <Button isOutlined color="is-primary">Outlined</Button>
      <Button isOutlined color="is-success">Outlined</Button>
      <Button isOutlined color="is-danger">Outlined</Button>
      <Button isOutlined color="is-warning">Outlined</Button>
      <Button isOutlined color="is-info">Outlined</Button>
      <Button isOutlined color="is-link">Outlined</Button>
    </Buttons>
    <Buttons>
      <Button isInverted color="is-primary">Inverted</Button>
      <Button isInverted color="is-success">Inverted</Button>
      <Button isInverted color="is-danger">Inverted</Button>
      <Button isInverted color="is-warning">Inverted</Button>
      <Button isInverted color="is-info">Inverted</Button>
      <Button isInverted color="is-link">Inverted</Button>
    </Buttons>
    <Buttons>
      <Button isRounded color="is-primary">Rounded</Button>
      <Button isRounded color="is-success">Rounded</Button>
      <Button isRounded color="is-danger">Rounded</Button>
      <Button isRounded color="is-warning">Rounded</Button>
      <Button isRounded color="is-info">Rounded</Button>
      <Button isRounded color="is-link">Rounded</Button>
    </Buttons>
  </Section>

  <Section>
    <Title type="subtitle" size="is-4">States</Title>
    <Title type="subtitle" size="is-6">Loading</Title>
    <Buttons>
      <Button isLoading color="is-primary">Primary</Button>
      <Button isLoading color="is-success">Success</Button>
      <Button isLoading color="is-danger">Danger</Button>
      <Button isLoading color="is-warning">Warning</Button>
      <Button isLoading color="is-info">Info</Button>
      <Button isLoading color="is-link">Link</Button>
    </Buttons>
    <Title type="subtitle" size="is-6">Static</Title>
    <Buttons>
      <Button isStatic color="is-primary">Static</Button>
      <Button isStatic color="is-success">Static</Button>
      <Button isStatic color="is-danger">Static</Button>
      <Button isStatic color="is-warning">Static</Button>
      <Button isStatic color="is-info">Static</Button>
      <Button isStatic color="is-link">Static</Button>
    </Buttons>
    <Title type="subtitle" size="is-6">Disabled</Title>
    <Buttons>
      <Button disabled color="is-primary">Disabled</Button>
      <Button disabled color="is-success">Disabled</Button>
      <Button disabled color="is-danger">Disabled</Button>
      <Button disabled color="is-warning">Disabled</Button>
      <Button disabled color="is-info">Disabled</Button>
      <Button disabled color="is-link">Disabled</Button>
    </Buttons>
  </Section>

  <Section>
    <Title type="subtitle" size="is-4">Buttons</Title>
    <Buttons>
      <Button>Button</Button>
      <Button>Button</Button>
      <Button>Button</Button>
      <Button>Button</Button>
    </Buttons>
  </Section>

  <Section>
    <Title type="subtitle" size="is-4">Button addons</Title>
    <Buttons hasAddons>
      <Button>Button</Button>
      <Button>Button</Button>
      <Button>Button</Button>
      <Button>Button</Button>
    </Buttons>
    <Buttons hasAddons>
      <Button isRounded>Button</Button>
      <Button isRounded>Button</Button>
      <Button isRounded>Button</Button>
      <Button isRounded>Button</Button>
    </Buttons>
  </Section>
</Container>
