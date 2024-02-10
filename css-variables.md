:root {
  --background-color-overlay: rgba(255,255,255,0.95);
  --background-color-overlay--lighter: rgba(255,255,255,0.6);
  --background-color-icon: rgba(0,0,0,0.6);
  --background-color-icon--hover: rgba(0,0,0,0.8);
  --background-color-icon--active: #000000;
  --background-color-quiet--hover: rgba(0,0,0,0.07000000000000001);
  --background-color-quiet--active: rgba(0,0,0,0.09);
  --color-destructive: #dd3333;
  --color-destructive--hover: #e35b5b;
  --color-destructive--active: #b32424;
  --color-warning: #ffcc33;
  --color-success: #00af89;
  --color-text-error: #dd3333;
  --color-text-warning: #ac6600;
  --color-text-success: #14866d;
  --color-link-new: #dd3333;
  --color-link-new--hover: #e35b5b;
  --color-link-new--active: #b32424;
  --color-syntax-red: #e53935;
  --color-syntax-orange: #f76d47;
  --color-syntax-yellow: #e2931d;
  --color-syntax-green: #91b859;
  --color-syntax-cyan: #39adb5;
  --color-syntax-blue: #6182b8;
  --color-syntax-paleblue: #8796b0;
  --color-syntax-purple: #9c3eda;
  --color-syntax-brown: #916b53;
  --color-syntax-pink: #ff5370;
  --color-syntax-violet: #945eb8;
  --color-syntax-grey: #90a4ae;
  --opacity-base--disabled: 0.3;
  --opacity-icon-base: 0.6;
  --opacity-icon-base--hover: 0.8;
  --opacity-icon-base--active: 1;
  --size-icon: 1.25rem;
  --border-color-base: rgba(0,0,0,0.05);
  --border-color-base--lighter: rgba(0,0,0,0.02);
  --border-color-base--darker: rgba(0,0,0,0.08);
  --border-color-input: rgba(0,0,0,0.05);
  --border-color-input--hover: rgba(0,0,0,0.4);
  --border-radius--small: 4px;
  --border-radius--medium: 8px;
  --border-radius--large: 12px;
  --border-radius--pill: 9999px;
  --font-family-base: var(--font-family-citizen-base),var(--font-family-language-base),system-ui,-apple-system,sans-serif;
  --font-family-serif: var(--font-family-citizen-serif),var(--font-family-language-serif),'Linux Libertine','Georgia','Times','Source Serif Pro',serif;
  --font-family-monospace: var(--font-family-citizen-monospace),var(--font-family-language-monospace),'Menlo','Consolas','Liberation Mono','Fira Code','Courier New',monospace;
  --font-family-citizen-base: 'Roboto';
  --font-family-citizen-serif: 'Roboto Serif';
  --font-family-citizen-monospace: 'Roboto Mono';
  --font-family-language-base: '';
  --font-family-language-serif: '';
  --font-family-language-monospace: '';
  --font-size-h1: 1.75rem;
  --font-size-h2: 1.375rem;
  --font-size-h3: 1.125rem;
  --font-size-h4: 1rem;
  --font-size-h5: 1rem;
  --font-size-h6: 1rem;
  --font-weight-normal: 400;
  --font-weight-medium: calc(var(--font-weight-normal) + 100);
  --font-weight-semibold: calc(var(--font-weight-normal) + 200);
  --font-weight-bold: calc(var(--font-weight-normal) + 300);
  --transition-hover: 150ms cubic-bezier(0.215,0.61,0.355,1);
}
html {
  font-size: 100%;
}
  @media (min-width: 1120px)
html {
  --padding-page: 32px;
  --header-card-maxheight: calc(100vh - var(--space-sm) * 2);
}
  @media (min-width: 640px)
html {
  --padding-page: 24px;
}
html {
  --header-size: 3.5rem;
  --header-card-maxheight: 70vh;
  --width-layout: 1080px;
  --width-layout--extended: calc(var(--width-layout) * 1.5);
  --width-toc: 240px;
  --line-height: 1.6;
  --line-height-xs: 1.25;
  --line-height-sm: 1.375;
  --space-unit: 1rem;
  --space-xxs: calc(0.25 * var(--space-unit));
  --space-xs: calc(0.5 * var(--space-unit));
  --space-sm: calc(0.75 * var(--space-unit));
  --space-md: var(--space-unit);
  --space-lg: calc(1.25 * var(--space-unit));
  --space-xl: calc(1.5 * var(--space-unit));
  --space-xxl: calc(2 * var(--space-unit));
  --margin-layout: calc((100vw - var(--width-layout)) / 2);
  --padding-page: 16px;
}

root.skin-citizen-dark {
  --background-color-icon: rgba(255,255,255,0.6);
  --background-color-icon--hover: rgba(255,255,255,0.8);
  --background-color-icon--active: rgba(255,255,255,0.4);
  --background-color-quiet--hover: rgba(255,255,255,0.07000000000000001);
  --background-color-quiet--active: rgba(255,255,255,0.03);
  --color-text-error: #e35b5b;
  --color-text-warning: #ffcc33;
  --color-text-success: #00af89;
  --color-link-new: #e35b5b;
  --color-link-new--hover: #fee7e6;
  --color-link-new--active: #b32424;
  --color-syntax-red: #f07178;
  --color-syntax-orange: #f78c6c;
  --color-syntax-yellow: #ffcb6b;
  --color-syntax-green: #c3e88d;
  --color-syntax-cyan: #89ddff;
  --color-syntax-blue: #82aaff;
  --color-syntax-paleblue: #b2ccd6;
  --color-syntax-purple: #c792ea;
  --color-syntax-brown: #916b53;
  --color-syntax-pink: #ff9cac;
  --color-syntax-violet: #bb80b3;
  --opacity-icon-base--active: 0.4;
  --border-color-base: rgba(255,255,255,0.05);
  --border-color-base--lighter: rgba(255,255,255,0.02);
  --border-color-base--darker: rgba(255,255,255,0.08);
  --border-color-input: rgba(255,255,255,0.05);
  --border-color-input--hover: rgba(255,255,255,0.5);
}

/* real variables*/

/*
 * Citizen - CSS variables
 * https://starcitizen.tools
 */

@import '../../variables.less';

/**
 * Base theme
 */
:root {
	--background-color-overlay: @background-color-overlay;
	--background-color-overlay--lighter: @background-color-overlay--lighter;

	--background-color-icon: @background-color-icon;
	--background-color-icon--hover: @background-color-icon--hover;
	--background-color-icon--active: @background-color-icon--active;
	--background-color-quiet--hover: @background-color-quiet--hover;
	--background-color-quiet--active: @background-color-quiet--active;

	/* Foreground Colors */
	--color-destructive: @color-destructive;
	--color-destructive--hover: @color-destructive--hover;
	--color-destructive--active: @color-destructive--active;

	--color-warning: @color-warning;
	--color-success: @color-success;

	--color-text-error: @color-text-error;
	--color-text-warning: @color-text-warning;
	--color-text-success: @color-text-success;

	--color-link-new: @color-link-new;
	--color-link-new--hover: @color-link-new--hover;
	--color-link-new--active: @color-link-new--active;

	--color-syntax-red: @color-syntax-red;
	--color-syntax-orange: @color-syntax-orange;
	--color-syntax-yellow: @color-syntax-yellow;
	--color-syntax-green: @color-syntax-green;
	--color-syntax-cyan: @color-syntax-cyan;
	--color-syntax-blue: @color-syntax-blue;
	--color-syntax-paleblue: @color-syntax-paleblue;
	--color-syntax-purple: @color-syntax-purple;
	--color-syntax-brown: @color-syntax-brown;
	--color-syntax-pink: @color-syntax-pink;
	--color-syntax-violet: @color-syntax-violet;
	--color-syntax-grey: @color-syntax-grey;

	/* Opacity */
	--opacity-base--disabled: @opacity-base--disabled;
	--opacity-icon-base: @opacity-icon-base;
	--opacity-icon-base--hover: @opacity-icon-base--hover;
	--opacity-icon-base--active: @opacity-icon-base--active;

	/* Size */
	--size-icon: @size-icon;

	/* Border Colors */
	--border-color-base: @border-color-base;
	--border-color-base--lighter: @border-color-base--lighter;
	--border-color-base--darker: @border-color-base--darker;
	--border-color-input: @border-color-input;
	--border-color-input--hover: @border-color-input--hover;

	/* Border radius */
	--border-radius--small: @border-radius--small;
	--border-radius--medium: @border-radius--medium;
	--border-radius--large: @border-radius--large;
	--border-radius--pill: @border-radius--pill;

	/* Fonts */
	--font-family-base: @font-family-base;
	--font-family-serif: @font-family-serif;
	--font-family-monospace: @font-family-monospace;
	--font-family-citizen-base: 'Roboto';
	--font-family-citizen-serif: 'Roboto Serif';
	--font-family-citizen-monospace: 'Roboto Mono';
	--font-family-language-base: '';
	--font-family-language-serif: '';
	--font-family-language-monospace: '';

	--font-size-h1: 1.75rem;
	--font-size-h2: 1.375rem;
	--font-size-h3: 1.125rem;
	--font-size-h4: 1rem;
	--font-size-h5: 1rem;
	--font-size-h6: 1rem;

	--font-weight-normal: 400;
	--font-weight-medium: ~'calc( var( --font-weight-normal ) + 100)';
	--font-weight-semibold: ~'calc( var( --font-weight-normal ) + 200)';
	--font-weight-bold: ~'calc( var( --font-weight-normal ) + 300)';

	/* Transitions */
	--transition-hover: @transition-hover;
}

html {
	/* Size */
	--header-size: @header-size;
	--header-card-maxheight: 70vh;
	--width-layout: @width-layout;
	--width-layout--extended: ~'calc( var( --width-layout ) * 1.5 )';
	--width-toc: @width-toc;
	--line-height: @line-height-md;
	--line-height-xs: @line-height-xs;
	--line-height-sm: @line-height-sm;

	/* Spacing */
	--space-unit: @space-unit;
	--space-xxs: ~'calc( 0.25 * var( --space-unit ) )';
	--space-xs: ~'calc( 0.5 * var( --space-unit ) )';
	--space-sm: ~'calc( 0.75 * var( --space-unit ) )';
	--space-md: ~'var( --space-unit )';
	--space-lg: ~'calc( 1.25 * var( --space-unit ) )';
	--space-xl: ~'calc( 1.5 * var( --space-unit ) )';
	--space-xxl: ~'calc( 2 * var( --space-unit ) )';

	/* Margin */
	--margin-layout: ~'calc( ( 100vw - var( --width-layout ) ) / 2 )';

	/* Padding */
	--padding-page: @padding-page;
}

/**
 * Dark theme
 */
:root.skin-citizen-dark {
	--background-color-icon: @dark-background-color-icon;
	--background-color-icon--hover: @dark-background-color-icon--hover;
	--background-color-icon--active: @dark-background-color-icon--active;
	--background-color-quiet--hover: @dark-background-color-quiet--hover;
	--background-color-quiet--active: @dark-background-color-quiet--active;

	--color-text-error: @dark-color-text-error;
	--color-text-warning: @dark-color-text-warning;
	--color-text-success: @dark-color-text-success;

	--color-link-new: @dark-color-link-new;
	--color-link-new--hover: @dark-color-link-new--hover;
	--color-link-new--active: @dark-color-link-new--active;

	--color-syntax-red: @color-syntax-red-dark;
	--color-syntax-orange: @color-syntax-orange-dark;
	--color-syntax-yellow: @color-syntax-yellow-dark;
	--color-syntax-green: @color-syntax-green-dark;
	--color-syntax-cyan: @color-syntax-cyan-dark;
	--color-syntax-blue: @color-syntax-blue-dark;
	--color-syntax-paleblue: @color-syntax-paleblue-dark;
	--color-syntax-purple: @color-syntax-purple-dark;
	--color-syntax-brown: @color-syntax-brown-dark;
	--color-syntax-pink: @color-syntax-pink-dark;
	--color-syntax-violet: @color-syntax-violet-dark;

	/* Opacity */
	--opacity-icon-base--active: @dark-opacity-icon-base--active;

	/* Border Colors */
	--border-color-base: @dark-border-color-base;
	--border-color-base--lighter: @dark-border-color-base--lighter;
	--border-color-base--darker: @dark-border-color-base--darker;
	--border-color-input: @dark-border-color-input;
	--border-color-input--hover: @dark-border-color-input--hover;
}

@media ( min-width: @min-width-breakpoint-tablet ) {
	:root {
		--font-size-h1: 2rem;
		--font-size-h2: 1.5rem;
		--font-size-h3: 1.25rem;
		--font-size-h4: 1.125rem;
	}

	html {
		--padding-page: @padding-page * 1.5;
	}
}

@media ( min-width: @min-width-breakpoint-desktop ) {
	html {
		--padding-page: @padding-page * 2;
		--header-card-maxheight: ~'calc( 100vh - var( --space-sm ) * 2 )';
	}
}

@media ( prefers-contrast: more ) {
	:root {
		--font-weight-normal: 500;
	}
}

@media ( prefers-contrast: less ) {
	:root {
		--font-weight-normal: 300;
	}
}

.citizen-animations-ready {
	/* Only apply transition when page is ready for it */
	--transition-menu: @transition-menu;
}