<script>
  import 'bulma-svelte/src/styles/main.css';
  import { Button, Anchor, Column, Columns, Container, Menu, MenuLabel, MenuList, MenuListItem } from 'bulma-svelte';
  export let segment;
  segment = !segment;
</script>

<main>
  <Container isFluid>
    <Columns>
      <Column class="has-background-light" isNarrow>
        <Menu>
          <MenuList>
            <Anchor color="has-text-primary" href="/">Home</Anchor>
          </MenuList>
          <MenuLabel label="LAYOUT" />
          <MenuList>
            <MenuListItem text="Container" href="/layout/container" />
            <MenuListItem text="Level" href="/layout/level" />
            <MenuListItem text="Hero" href="/layout/hero" />
            <MenuListItem text="Section" href="/layout/section" />
            <MenuListItem text="Footer" href="/layout/footer" />
            <MenuListItem text="Tiles" href="/layout/tiles" />
            <MenuListItem text="Media Object" href="/layout/media-object" />
          </MenuList>
          <MenuLabel label="COLUMNS" />
          <MenuList>
            <MenuListItem text="Basic" href="/columns/basic" />
            <MenuListItem text="Sizes" href="/columns/sizes" />
            <MenuListItem text="Responsiveness" href="/columns/responsiveness" />
            <MenuListItem text="Nasting" href="/columns/nasting" />
            <MenuListItem text="Gap" href="/columns/gap" />
            <MenuListItem text="Options" href="/columns/options" />
          </MenuList>
          <MenuLabel label="ELEMENTS" />
          <MenuList>
            <MenuListItem text="Block" href="/elements/block" />
            <MenuListItem text="Box" href="/elements/box" />
            <MenuListItem text="Button" href="/elements/button" />
            <MenuListItem text="Content" href="/elements/content" />
            <MenuListItem text="Delete" href="/elements/delete" />
            <MenuListItem text="Icon" href="/elements/icon" />
            <MenuListItem text="Image" href="/elements/image" />
            <MenuListItem text="Notification" href="/elements/notification" />
            <MenuListItem text="Progress Bars" href="/elements/progress" />
            <MenuListItem text="Table" href="/elements/table" />
            <MenuListItem text="Tag" href="/elements/tag" />
            <MenuListItem text="Title" href="/elements/title" />
            <MenuListItem text="Anchor" href="/elements/anchor" />
          </MenuList>

          <MenuLabel label="COMPONENTS" />
          <MenuList>
            <MenuListItem text="Breadcrumb" href="/elements/breadcrumb" />
            <MenuListItem text="Card" href="/elements/card" />
            <MenuListItem text="Dropdown" href="/elements/dropdown" />
            <MenuListItem text="Menu" href="/elements/menu" />
            <MenuListItem text="Message" href="/elements/message" />
            <MenuListItem text="Modal" href="/elements/modal" />
            <MenuListItem text="Navbar" href="/elements/navbar" />
            <MenuListItem text="Pagination" href="/elements/pagination" />
            <MenuListItem text="Panel" href="/elements/panel" />
            <MenuListItem text="Tabs" href="/elements/tabs" />
          </MenuList>

          <MenuLabel label="FORM" />
          <MenuList>
            <MenuListItem text="General" href="/form/general" />
            <MenuListItem text="Input" href="/form/input" />
            <MenuListItem text="Textarea" href="/form/textarea" />
            <MenuListItem text="Select" href="/form/select" />
            <MenuListItem text="Checkbox" href="/form/checkbox" />
            <MenuListItem text="Radio" href="/form/radio" />
            <MenuListItem text="File" href="/form/file" />
          </MenuList>
        </Menu>
      </Column>
      <Column><slot /></Column>
    </Columns>
  </Container>
</main>

<style>
</style>
